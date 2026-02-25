# SECTION 1 — What you will build
You will launch a mobile-first, premium-looking 5-page Framer website for **Celina Fence & Gate Co.** that captures leads from Google, routes them into an Airtable pipeline, and automatically sends internal alerts plus lead follow-ups. Your **Get Estimate** form (Tally or Fillout) will collect project details, photos, and timeline, then Zapier automations will log each lead, notify your team, send confirmation emails, remind you if no one responds in 15 minutes, and optionally generate an AI “instant estimate range” (with a clear disclaimer that final pricing is confirmed after on-site measurement).

# SECTION 2 — One-time info I need from you (5 items max)
Use these defaults if you want to launch tonight and refine later:

1. **Brand Name:** `Celina Fence & Gate Co.`
2. **Primary Phone Number:** `(469) 555-0123`
3. **Estimate Email Inbox:** `estimates@celinafenceco.com`
4. **Service Area Confirmed:** `Celina, Prosper, Frisco, McKinney`
5. **Offer + Response Promise:** `Free on-site measurement + same day / within 24 hours response`

# SECTION 3 — Framer Site Build: click-by-click
## A) Project setup (Framer)
1. Open Framer → **New Project** → choose a clean business template (minimal/light).
2. Project Name: **Celina Fence & Gate Co.**
3. In left sidebar, create pages:
   - Home (`/`)
   - Fence Installation (`/fence-installation`)
   - Fence Repair (`/fence-repair`)
   - About (`/about`)
   - Get Estimate (`/get-estimate`)
4. In **Site Settings → Domains**, connect your domain (or publish to Framer subdomain first).
5. In **Site Settings → SEO**, set default title format: `{{page.title}} | Celina Fence & Gate Co.`

## B) Global styles (premium but attainable)
In Framer, go to **Styles** and set:
- **Font Pairing:**
  - Headings: `Plus Jakarta Sans` (or `Inter` if unavailable)
  - Body: `Inter`
- **Type scale:**
  - H1: 44/52, semibold
  - H2: 34/42, semibold
  - H3: 26/34, medium
  - Body: 18/30
  - Small: 15/24
- **Colors:**
  - Background: `#F8FAFC`
  - Surface/Cards: `#FFFFFF`
  - Text Primary: `#0F172A`
  - Text Secondary: `#475569`
  - Brand Accent: `#0EA5A4` (buttons/links)
  - Dark Accent: `#0B1324` (footer/background blocks)
- **Spacing system:** 8px base scale (8, 16, 24, 32, 48, 64, 96)
- **Buttons:**
  - Primary: teal fill, white text, 12px radius, 16px 24px padding
  - Secondary: white fill, dark border, dark text

## C) Header + footer spec
### Header (sticky)
- Left: logo text `Celina Fence & Gate Co.`
- Center/right nav links: Home, Fence Installation, Fence Repair, About, Get Estimate
- CTA button in header: **Get Free Estimate** (links to `/get-estimate`)
- Mobile: hamburger + persistent sticky bottom call bar

### Footer
Include 3 columns:
1. **Company**: About, Get Estimate, Service Area
2. **Services**: Fence Installation, Fence Repair, Gates
3. **Contact**: phone, email, hours, city

Footer trust line:
> We coordinate insured local install teams. Free on-site measurement. Clear scopes. Fast estimates.

Footer legal line:
> © 2026 Celina Fence & Gate Co. All rights reserved.

## D) Navigation + conversion behavior
- Every page must have:
  - Top-right CTA button: **Get Free Estimate**
  - Mid-page CTA strip
  - Bottom CTA before footer
- Mobile requirements:
  - Sticky call button: `Call (469) 555-0123`
  - CTA appears within first screen on every page
  - Form starts above the fold on Get Estimate page

## E) Page-by-page layout + exact copy
## 1) Home page sections (in order)
### Hero
**Headline:**
> Premium Fence Installation & Repair in Celina, TX

**Subhead:**
> Fast estimates, clear scopes, and insured local install partners for cedar, horizontal, iron, and chain link fences.

**Primary CTA:** `Get Free Estimate`
**Secondary CTA:** `Call (469) 555-0123`

**Trust bullets (inline under CTAs):**
- Free on-site measurement
- Same day / within 24 hours response
- 1-year workmanship warranty through our install partners

### Service Area Strip
> Serving **Celina** and nearby: Prosper, Frisco, McKinney.

### Services Grid (3 cards)
1. **Fence Installation**
   - New fence planning, materials, layout, and full install coordination.
2. **Fence Repair**
   - Posts, panels, gates, storm damage, and targeted repairs.
3. **Gate Upgrades**
   - Walk gates and driveway gate solutions with better function and curb appeal.

### Why Choose Us
**Section title:**
> Why Homeowners Choose Celina Fence & Gate Co.

**3 pillars:**
1. **Fast, organized process** — from intake to measurement to quote without the usual back-and-forth.
2. **Clear scopes and communication** — know exactly what’s included before work starts.
3. **Craftsmanship through vetted install partners** — we coordinate insured local teams focused on quality details.

### Social Proof Block
**Headline:**
> Built for homeowners who want it done right the first time.

**Body:**
> Whether you need a full replacement or a focused repair, we help you compare options, understand tradeoffs, and move quickly.

### FAQ Preview (link to full FAQ on Home + About)
- Do I need HOA approval?
- Do you handle old fence removal?
- Repair or replace — how do I decide?

### Final CTA
**Headline:**
> Get your fence project scoped fast.

**Subhead:**
> Tell us a few details and get a clear next step.

**CTA:** `Start My Estimate`

## 2) Fence Installation page
### Hero
**Headline:**
> Fence Installation in Celina, TX

**Subhead:**
> Cedar, horizontal, iron, and chain link options with free on-site measurement and clear project scope.

### Materials section
**Headline:**
> Material Options

**Cards:**
- **Cedar Privacy:** warm appearance, popular for backyard privacy
- **Horizontal Fence:** modern look, clean architectural lines
- **Ornamental Iron:** security + visibility with premium curb appeal
- **Chain Link:** practical, durable, and budget-friendly

### Process section
**Headline:**
> Our Installation Process

1. Submit estimate request
2. Quick call to confirm goals
3. On-site measurement
4. Written scope + quote
5. Install scheduling with insured local team

### CTA strip
> Ready to plan your new fence? Get a fast estimate today.

## 3) Fence Repair page
### Hero
**Headline:**
> Fence Repair in Celina, TX

**Subhead:**
> Fix leaning posts, broken panels, damaged gates, and storm wear before problems spread.

### Common repairs list
- Leaning or rotted posts
- Warped or broken boards/panels
- Gate sagging/misalignment
- Hardware/latch replacement
- Selective section rebuilds

### Repair vs Replace section
**Headline:**
> Repair vs Replace: We’ll help you choose

**Body:**
> If your fence has isolated damage, repair may be the best value. If structure, alignment, or age issues are widespread, replacement is often more cost-effective long-term.

### CTA strip
> Upload photos for a faster recommendation.

## 4) About page
### Hero
**Headline:**
> Local coordination. Better install experience.

**Body:**
> Celina Fence & Gate Co. helps homeowners plan fence projects and coordinates insured local install partners. Our focus is speed, communication, and quality outcomes.

### Values section
- **Responsive:** same day / within 24 hours follow-up
- **Transparent:** clear scopes before work starts
- **Quality-focused:** trusted install partners and finish details

### Trust section copy
> We coordinate insured local install teams and provide clear expectations from measurement to completion.

### CTA
> Need help with a fence project in Celina or nearby? Let’s start with a free measurement.

## 5) Get Estimate page
### Top copy
**Headline:**
> Get Your Free Fence Estimate

**Subhead:**
> Share your project details in 2–3 minutes. We’ll follow up same day or within 24 hours.

### Short reassurance above form
- No obligation
- Fast response
- Final quote after on-site measurement

(Embed form here — see Section 4)

### FAQs (exact copy)
1. **Do you work with HOA requirements?**
   - Yes. We can quote to common HOA-friendly styles and help you gather specs for approval.
2. **Do I need a permit for a new fence?**
   - Permit requirements vary by city and project scope. We’ll flag what to verify before install.
3. **Can you stain or seal my fence?**
   - Yes, staining/sealing can be included as an add-on depending on material and timing.
4. **How long does installation take?**
   - Most residential projects are completed in a few days after scope approval and scheduling.
5. **What materials do you offer?**
   - Cedar, horizontal wood styles, ornamental iron, and chain link.
6. **Can you add or replace gates?**
   - Yes. We handle walk gates and driveway gate coordination.
7. **Do you remove old fencing?**
   - Yes, removal/disposal can be included in your scope.
8. **How do I decide between repair and replacement?**
   - We assess structural condition, lifespan, and cost tradeoffs, then recommend the best-value option.

## F) Image guidance (what to upload)
Use real, local-style residential images with clean lighting and no heavy filters.

Suggested image search phrases (6):
1. `new cedar privacy fence backyard texas`
2. `horizontal wood fence modern home exterior`
3. `ornamental iron fence front yard`
4. `chain link fence residential side yard`
5. `fence gate close up hardware`
6. `fence installation team measuring yard`

## G) SEO settings per page
Set these in each page’s **SEO** panel in Framer:

- **Home**
  - Title: `Fence Installation & Repair in Celina, TX | Celina Fence & Gate Co.`
  - Meta: `Premium-but-attainable fence installation and repair in Celina. Free on-site measurement, fast estimates, and insured local install partners.`

- **Fence Installation**
  - Title: `Fence Installation Celina, TX | Cedar, Iron, Horizontal, Chain Link`
  - Meta: `Professional fence installation coordination in Celina with clear scopes, material options, and free on-site measurement.`

- **Fence Repair**
  - Title: `Fence Repair Celina, TX | Posts, Panels, Gates`
  - Meta: `Fast fence repair in Celina for leaning posts, broken panels, and damaged gates. Get a clear recommendation and estimate.`

- **About**
  - Title: `About Celina Fence & Gate Co. | Local Fence Project Coordination`
  - Meta: `Learn how we coordinate insured local install partners for quality fence installation and repair in Celina and nearby suburbs.`

- **Get Estimate**
  - Title: `Get Fence Estimate in Celina, TX | Free On-Site Measurement`
  - Meta: `Request your free fence estimate in Celina. Share project details and photos for a fast response within 24 hours.`

## H) Tracking readiness (GA4 + optional call tracking)
### GA4 (required)
1. Go to analytics.google.com → create GA4 property `Celina Fence & Gate Co`.
2. Create Web Data Stream for your domain.
3. Copy Measurement ID (`G-XXXXXXXXXX`).
4. In Framer: **Site Settings → Analytics** → paste GA4 Measurement ID.
5. Publish site, then open GA4 Realtime and verify your visit appears.

### Optional CallRail
1. Create a CallRail tracking number.
2. Set destination to your main business line.
3. Enable website number swap script in CallRail.
4. In Framer: **Site Settings → Custom Code → End of body** paste CallRail script.
5. Replace visible phone text/buttons with tracking number.

# SECTION 4 — Get Estimate Form: Tally/Fillout build
## A) Build in Tally (preferred)
1. Go to Tally → **Create Form** → Blank Form.
2. Form Title: `Get Your Free Fence Estimate`
3. Add description: `Complete this in 2–3 minutes. We respond same day or within 24 hours.`

## B) Exact fields and types
Create fields in this order:
1. **Full Name** — Short text — Required
2. **Phone** — Phone — Required
3. **Email** — Email — Required
4. **Address** — Short text — Required
5. **City** — Dropdown (`Celina`, `Prosper`, `Frisco`, `McKinney`, `Other`) — Required
6. **Service Type** — Multiple choice single select (`Install`, `Repair`) — Required
7. **Fence Material** — Multiple choice single select (`Cedar`, `Horizontal`, `Iron`, `Chain Link`, `Other`) — Required
8. **Approx Linear Footage** — Number — Required
9. **Remove old fence?** — Yes/No — Required
10. **Gates needed?** — Multiple choice single select (`0`, `1`, `2+`) — Required
11. **HOA?** — Multiple choice single select (`Yes`, `No`, `Unsure`) — Required
12. **Timeline** — Multiple choice single select (`ASAP`, `30 days`, `60+ days`) — Required
13. **Notes** — Long text — Optional
14. **Upload Photos (optional)** — File upload (up to 5 files) — Optional

## C) Conditional logic
Set logic rules:
- If **Service Type = Repair**:
  - Show helper text under Notes: `Please describe damaged sections (posts, panels, gates) and urgency.`
- If **Service Type = Install**:
  - Show helper text: `Share preferred style, privacy goals, and any HOA constraints.`
- If **Remove old fence? = Yes**:
  - Show follow-up field: `Old fence type/condition` (short text, optional)
- If **Gates needed? = 1 or 2+**:
  - Show follow-up field: `Gate type` (single select: `Walk Gate`, `Driveway Gate`, `Not Sure`)

## D) Confirmation message (after submit)
> Thanks — your request was received.
> We’ll review your details and contact you same day or within 24 hours.
> For urgent requests, call (469) 555-0123.

## E) Lead email confirmation copy
**Subject:** We got your fence estimate request

**Body:**
Hi {{Full Name}},

Thanks for contacting Celina Fence & Gate Co. We received your request and will follow up same day or within 24 hours.

What happens next:
1) Quick review of your project details/photos
2) Follow-up to confirm scope
3) On-site measurement and written quote

If your request is urgent, call us at (469) 555-0123.

– Celina Fence & Gate Co.

## F) Internal notification copy
**Subject:** New Fence Lead — {{Service Type}} — {{City}}

**Body:**
New lead received.

Name: {{Full Name}}
Phone: {{Phone}}
Email: {{Email}}
Address: {{Address}}, {{City}}
Service Type: {{Service Type}}
Material: {{Fence Material}}
Approx LF: {{Approx Linear Footage}}
Remove old fence: {{Remove old fence?}}
Gates: {{Gates needed?}}
HOA: {{HOA?}}
Timeline: {{Timeline}}
Notes: {{Notes}}

Open Airtable to assign and respond.

## G) Spam prevention suggestions
- Turn on Tally built-in spam protection (honeypot + rate limit).
- Add reCAPTCHA if available on your plan.
- Require phone + email.
- Add hidden field `Website` (leave blank) to trap bots.

## H) Embed into Framer (copy/paste)
1. In Tally, click **Share → Embed**.
2. Copy the embed snippet.
3. In Framer, open **Get Estimate** page → insert **Embed** component.
4. Paste snippet and set width 100%, min height 900px.
5. Publish and test on mobile.

(Alternate: Fillout has the same flow — create fields, copy embed, paste in Framer Embed block.)

# SECTION 5 — Airtable setup (Leads pipeline)
## A) Base and tables
- **Base name:** `Celina Fence Leads`
- **Primary table:** `Leads`
- **Optional table:** `Install Partners`

## B) Leads table — exact fields
1. `Lead ID` — Autonumber
2. `Created Time` — Created time
3. `Full Name` — Single line text
4. `Phone` — Phone number
5. `Email` — Email
6. `Address` — Single line text
7. `City` — Single select (Celina, Prosper, Frisco, McKinney, Other)
8. `Service Type` — Single select (Install, Repair)
9. `Fence Material` — Single select (Cedar, Horizontal, Iron, Chain Link, Other)
10. `Approx Linear Footage` — Number (integer)
11. `Remove old fence?` — Single select (Yes, No)
12. `Gates needed?` — Single select (0, 1, 2+)
13. `HOA?` — Single select (Yes, No, Unsure)
14. `Timeline` — Single select (ASAP, 30 days, 60+ days)
15. `Notes` — Long text
16. `Photo Upload URLs` — Long text
17. `Status` — Single select (New, Contacted, Scheduled, Quoted, Won, Lost)
18. `Assigned To` — Collaborator (or single select if no Airtable users)
19. `First Response Sent` — Checkbox
20. `Last Contacted At` — Date/time
21. `Follow-up Needed` — Formula (optional)
22. `AI Estimate Range` — Long text
23. `AI Price Factors` — Long text
24. `AI Suggested Next Step` — Long text
25. `Project Completion Date` — Date
26. `Review Request Sent` — Checkbox

## C) Suggested views
- **New** → filter `Status = New`
- **Contacted** → filter `Status = Contacted`
- **Scheduled** → filter `Status = Scheduled`
- **Quoted** → filter `Status = Quoted`
- **Won** → filter `Status = Won`
- **Lost** → filter `Status = Lost`

## D) Simple status workflow
`New → Contacted → Scheduled → Quoted → Won/Lost`

Rule of thumb:
- Move to **Contacted** immediately after first call/email.
- Move to **Scheduled** once measurement time is offered/confirmed.
- Move to **Quoted** once written scope is sent.
- End at **Won** when approved, **Lost** when declined/unresponsive.

## E) Contractor assignment field
Use `Assigned To` for coordinator, and optionally add:
- `Install Partner` (link to `Install Partners` table)
- `Install Date` (date)

## F) Data protection + permissions
- Share Airtable base only with internal team.
- Use interface views for installers (limited fields).
- Do not store payment data in Airtable.
- Turn on 2FA for Airtable and email accounts.

# SECTION 6 — Automations (Zapier primary, Make optional)
## Zapier Recipe A
### A) New form submission → Airtable lead → internal email → lead confirmation email
**Zap name:** `Fence Lead Intake + Notifications`

1. **Trigger:** Tally — `New Form Response`
2. **Action:** Airtable — `Create Record` in `Celina Fence Leads` / `Leads`
   - Map all form fields exactly
   - Set `Status = New`
3. **Action:** Gmail (or Email by Zapier) — `Send Email` (internal)
   - To: estimates@celinafenceco.com
   - Subject/body: use internal template from Section 4F
4. **Action:** Gmail (or Email by Zapier) — `Send Email` (lead)
   - To: lead email
   - Subject/body: use template from Section 4E
5. **Action (optional):** Airtable — `Update Record`
   - Set `First Response Sent = checked`
   - Set `Last Contacted At = now`

## Zapier Recipe B
### B) If lead not contacted in 15 minutes → reminder ping
**Zap name:** `Fence Lead 15-Minute Reminder`

1. **Trigger:** Airtable — `New Record in View` (view = `New`)
2. **Action:** Delay by Zapier — `Delay For` 15 minutes
3. **Action:** Airtable — `Find Record` (same Lead ID)
4. **Filter:** Continue only if `Status` is still `New`
5. **Action:** Gmail or SMS (optional) reminder
   - Subject: `Reminder: New lead not contacted (15 min)`
   - Include name, phone, city, service type

## Zapier Recipe C
### C) If status becomes Scheduled → send calendar link template
**Zap name:** `Scheduled Status Follow-up`

1. **Trigger:** Airtable — `Updated Record` (watch `Status`)
2. **Filter:** Continue if `Status = Scheduled`
3. **Action:** Gmail — `Send Email` to lead

**Template:**
Subject: Your fence measurement scheduling link

Hi {{Full Name}},

Great — your project is now in scheduling.
Use this link to choose a measurement time: {{Your Calendar Link}}

If you prefer, reply to this email with 2–3 times that work for you.

– Celina Fence & Gate Co.

## Zapier Recipe D
### D) If status becomes Won → send review request 2 days after completion
**Zap name:** `Post-Completion Review Request`

1. **Trigger:** Airtable — `Updated Record`
2. **Filter:** `Status = Won` AND `Project Completion Date is not empty`
3. **Action:** Delay by Zapier — `Delay Until` = `Project Completion Date + 2 days`
4. **Action:** Gmail — send review request
5. **Action:** Airtable — update `Review Request Sent = checked`

**Review email copy:**
Subject: Quick favor — how did we do?

Hi {{Full Name}},

Thank you again for trusting Celina Fence & Gate Co.
If you’re happy with the result, would you mind leaving a quick review here?
{{Google Review Link}}

We appreciate your support.

## Zapier Recipe E (OPTIONAL AI Estimate Range)
### E) AI estimate range + explanation + next step
Add this after Recipe A’s Airtable Create step.

## 1) Simple pricing rules table (example starter ranges)
Use these conservative placeholder numbers and tune later:

- **Cedar:** $35–$55 per linear ft
- **Horizontal:** $45–$70 per linear ft
- **Iron:** $55–$95 per linear ft
- **Chain Link:** $25–$45 per linear ft
- **Other:** $35–$65 per linear ft
- **Old fence removal add-on:** +$6–$12 per linear ft
- **Gate add-on:**
  - 1 gate: +$250–$600
  - 2+ gates: +$500–$1,200

## 2) OpenAI step in Zapier
1. **Action:** OpenAI (Chat Completions) in Zapier
2. Model: lightweight GPT model supported in your account
3. Input variables from Airtable/form:
   - Service Type
   - Fence Material
   - Approx Linear Footage
   - Remove old fence?
   - Gates needed?
   - City

## 3) Exact prompt text to paste
You are an estimator assistant for a fence company in Celina, TX.
Generate a conservative budgetary estimate range using the pricing rules below.
Do not promise final pricing. Keep output concise and customer-friendly.

Pricing rules:
- Cedar: $35–$55 / linear ft
- Horizontal: $45–$70 / linear ft
- Iron: $55–$95 / linear ft
- Chain Link: $25–$45 / linear ft
- Other: $35–$65 / linear ft
- Removal add-on: +$6–$12 / linear ft if removal is Yes
- Gates: +$250–$600 for 1 gate, +$500–$1,200 for 2+ gates

Input lead data:
- Service Type: {{Service Type}}
- Material: {{Fence Material}}
- Linear Footage: {{Approx Linear Footage}}
- Remove old fence: {{Remove old fence?}}
- Gates needed: {{Gates needed?}}
- City: {{City}}

Output in JSON with keys:
estimate_range
price_factors
next_step
safe_disclaimer

Requirements:
- If service type is Repair, provide a broad repair range and explain it depends on damage severity.
- Include this exact disclaimer text in safe_disclaimer:
  "This is a budgetary range only. Final quote is provided after on-site measurement."
- next_step should recommend scheduling on-site measurement.

## 4) Store + send AI output
After OpenAI step:
1. **Airtable Update Record**
   - `AI Estimate Range` ← `estimate_range`
   - `AI Price Factors` ← `price_factors`
   - `AI Suggested Next Step` ← `next_step`
2. **Gmail Send Email** to lead:

Subject: Your preliminary fence estimate range

Hi {{Full Name}},

Based on your details, your preliminary estimate range is:
{{AI Estimate Range}}

What affects price most:
{{AI Price Factors}}

Recommended next step:
{{AI Suggested Next Step}}

This is a budgetary range only. Final quote is provided after on-site measurement.

## 5) Tune numbers later (important)
- Review 10–20 real quotes, then adjust per-material ranges.
- Increase removal/gate add-ons if labor and disposal costs rise.
- Keep AI ranges conservative to avoid underquoting.

## Make.com alternative (if not using Zapier)
Build one scenario per recipe with equivalent modules:
- **Trigger:** Tally Watch Responses
- **Airtable:** Create/Update record
- **Tools:** Sleep (15 min delay)
- **Router + Filter:** only if Status still New
- **Gmail/Twilio:** send notifications
- **OpenAI module:** generate estimate JSON
- **Airtable update + Gmail send:** write back AI fields + email lead

---
**Launch checklist (same evening):**
1. Publish Framer site.
2. Submit a test lead from mobile.
3. Confirm Airtable row created.
4. Confirm internal + lead emails arrive.
5. Test status change automations (Scheduled, Won).
6. Turn on GA4 + optional CallRail number swap.
