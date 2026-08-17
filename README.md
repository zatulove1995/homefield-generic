# Homefield — generic homeowner-leads site

Multi-page marketing site for Homefield: exclusive homeowner leads by email for **home services
businesses, home insurance agencies, real estate agents, and real estate investors**. One business per
industry per ZIP. Generic variant of the insurance-only site live at homefieldemail.com — same design system,
same "Direct mail results" hero and cost comparison, copy generalized to four audiences.

Pages: index · industries (new) · how-it-works · leads · compare · pricing · faq · contact · privacy · terms.
Shared: `styles.css` (`?v=nb2` cache key), `script.js` (nav, mobile menu, reveal, current-page highlight,
form → Calendly handoff). Page-scoped styles: `hm-` `in-` `hw-` `ld-` `cp-` `pr-` `fq-`.

All "Book a call" CTAs → https://calendly.com/zatulovebrian/call. Form falls back to Calendly with
name/email/notes prefilled while `FORM_ENDPOINT` is empty.

Before launch: replace sample replies/records (HTML-commented), fill privacy/terms brackets, set the
footer mailing address, source or adjust the sample figures ($40/$35/$30, CPA ranges, 275M+ records).

Local preview: `cd ~/Desktop/Claude/homefield-generic && python3 -m http.server 8810`
