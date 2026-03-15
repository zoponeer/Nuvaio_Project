# Nuvaio Travel — Instantly.ai Campaign Sequences
### Ready-to-Paste Email Campaigns for Corporate Travel & Event Travel

---

## SETUP BEFORE YOU LAUNCH

### Domain & Email Setup
1. **Buy a secondary domain** — `nuvaiotravel.co`, `travelwithNuvaio.com`, or `nuvaioair.com` (~$10/year on Namecheap)
2. **Create a mailbox** on it — `xavier@nuvaiotravel.co` (use Google Workspace at $7/month or Zoho Mail free tier)
3. **Set up DNS records** — SPF, DKIM, and DMARC. Instantly has a guide for this in their dashboard. Without these, you land in spam.
4. **Turn on Instantly's warm-up** — let it run for 14 days before sending any campaigns. This is non-negotiable.

### Instantly Settings
- **Emails per day per account:** Start at 15, increase to 25 after 2 weeks, max 40 after 4 weeks
- **Time between emails:** 3–5 minutes (Instantly randomizes this)
- **Sending window:** 8:00 AM – 11:30 AM in the recipient's timezone (Tuesday–Thursday get the best open rates)
- **Stop on reply:** ON (this pulls them out of the sequence when they respond)
- **Track opens:** ON
- **Track link clicks:** OFF (link tracking hurts deliverability for cold email)

### Personalization Variables
Instantly uses double-bracket variables. You'll set these up in your CSV upload:

| Variable | What it maps to | Example |
|---|---|---|
| {{firstName}} | Contact's first name | Sarah |
| {{company}} | Company name | Meridian Consulting |
| {{industry}} | Their industry | consulting |
| {{title}} | Their job title | Director of Operations |
| {{city}} | Their city | Dallas |
| {{custom1}} | Specific detail you noticed | recent expansion to 3 new offices |

---

## CAMPAIGN 1: CORPORATE TRAVEL TARGETS

**Target:** Office Managers, Directors of Operations, VPs of Finance, Travel Coordinators, Chiefs of Staff, Executive Assistants at companies with 50–500 employees.

**Campaign name in Instantly:** `Nuvaio — Corporate Travel — [Month]`

---

### Email 1 — The Question (Day 1)

**Subject line (A/B test both):**
- **A:** `Quick question about {{company}}'s travel`
- **B:** `How does {{company}} handle corporate travel?`

**Body:**

```
Hi {{firstName}},

I work with mid-size companies that have outgrown their current travel setup — usually stuck between a platform that doesn't flex and an agency that doesn't really know their business.

I'm curious: is {{company}} handling corporate air and travel in-house, or working with an outside partner?

Not trying to sell you anything — genuinely trying to understand how companies in {{industry}} are approaching this right now.

Xavier Phillips
Nuvaio Travel
975-444-0066
```

**Why this works:** It asks a question instead of pitching. Questions get replies. The framing ("outgrown their current setup") plants the seed that there's a better option without being pushy. It also signals that you understand their world — mid-size companies, platforms that don't flex — which builds credibility before you've even had a conversation.

---

### Email 2 — The Value Hook (Day 4)

**Subject line:** (same thread — no new subject, Instantly keeps the RE: chain)

**Body:**

```
Hi {{firstName}},

Following up briefly on my note. One pattern I keep seeing with companies around {{company}}'s size — they're leaving 15–20% on the table on corporate airfare because nobody's actively monitoring fare changes after booking or leveraging consolidator pricing.

Most platforms book and move on. We don't. We watch every active itinerary for schedule changes, cancellations, and price drops — and rebook proactively when it saves money.

If that's something {{company}} would benefit from, I'm happy to do a quick 15-minute review of your current travel spend. No cost, no commitment — sometimes a second set of eyes catches things.

Worth a conversation?

Xavier
975-444-0066
```

**Why this works:** This email gives them a specific, quantifiable reason to care (15–20% savings). It introduces a concrete differentiator (proactive monitoring and rebooking) that platforms don't do. The CTA is low-friction — "15-minute review" is easy to say yes to.

---

### Email 3 — The Proof Point (Day 8)

**Subject line:** (same thread)

**Body:**

```
{{firstName}} — one more thought, then I'll get out of your inbox.

The companies that typically get the most value from working with us have a few things in common:

— They have 10+ people traveling regularly and nobody dedicated to managing it
— Their travelers are booking inconsistently (some on the platform, some off)
— Finance spends too much time reconciling travel spend at quarter-end
— When something goes wrong after hours, there's no real escalation path

If any of that sounds familiar, a 15-minute call would probably be useful for both of us. I can share how we've structured travel programs for similar companies and you can decide if it's worth exploring.

Here's my calendar if it's easier: [INSERT CALENDLY LINK]

Xavier Phillips
Nuvaio Travel | nuvaiotravel.com
975-444-0066
```

**Why this works:** Instead of a generic follow-up, this paints a picture of their exact situation. If they see themselves in 2 or 3 of those bullets, the relevance jumps dramatically. The Calendly link removes friction — they can book without a back-and-forth email chain.

---

### Email 4 — The Breakup (Day 14)

**Subject line:** (same thread)

**Body:**

```
Hi {{firstName}},

I've reached out a few times and I know you're busy — don't want to be a pest.

If corporate travel management isn't a priority for {{company}} right now, totally understand. I'll close out the thread.

If it comes up down the road, I'm easy to find:
xavier@nuvaiotravel.com | 975-444-0066

All the best,
Xavier
```

**Why this works:** The breakup email consistently gets the highest reply rate in cold email sequences — sometimes 2–3x the other emails. It triggers loss aversion ("wait, maybe I should respond before they stop reaching out") and comes across as respectful, not desperate. Keep it short. Don't re-pitch.

---

## CAMPAIGN 2: EVENT & GROUP TRAVEL TARGETS

**Target:** Meeting Planners, Event Coordinators, Conference Directors, Association Executives, DMC Partners, Incentive Travel Planners.

**Campaign name in Instantly:** `Nuvaio — Event/Group Air — [Month]`

---

### Email 1 — The Opener (Day 1)

**Subject line (A/B test both):**
- **A:** `Group air for {{company}}'s events?`
- **B:** `Who handles air logistics for {{company}}'s conferences?`

**Body:**

```
Hi {{firstName}},

I noticed {{company}} runs [events / conferences / incentive trips] — and I'm curious who handles the air travel logistics for your attendees.

We specialize in exactly this at Nuvaio Travel: group air manifests, attendee flight coordination, name-change management, and onsite agent support for events from 10 to 500+ travelers.

Most event teams I talk to are either doing it themselves (painful) or handing it to a generalist agency that doesn't really understand event air (also painful). We sit in the middle — dedicated air specialists who do this every day.

Is this something {{company}} handles internally, or would it be worth a conversation?

Xavier Phillips
Nuvaio Travel
975-444-0066
```

**Why this works:** Event planners have a very specific pain — air logistics are a nightmare that most agencies handle poorly. This email names that pain directly and positions Nuvaio as the specialist, not the generalist. The question at the end makes it easy to reply.

---

### Email 2 — The Scenario (Day 4)

**Subject line:** (same thread)

**Body:**

```
Hi {{firstName}},

Following up on my note. Here's a quick picture of what working with Nuvaio looks like for event air:

You send us your attendee list. We build the full air manifest — routing, fare classes, special requests, loyalty numbers, the works. From there, we handle all the changes (and there are always changes) — name swaps, date shifts, cancellations — without your team touching it.

During the event, we provide onsite air agent support if needed. If flights get disrupted, we rebook your attendees before they even call you.

The event planners we work with tell us the same thing: "I didn't realize how much time we were spending on air until someone else handled it."

If you have an event coming up in the next 6 months, a 15-minute call could save your team a lot of headaches. Worth it?

Xavier
975-444-0066
```

**Why this works:** This walks them through the experience step by step — which is what event planners care about. They think in logistics and timelines. Showing the process (attendee list → manifest → changes → onsite support → disruption handling) makes the value tangible, not abstract.

---

### Email 3 — The Specificity Play (Day 9)

**Subject line:** (same thread)

**Body:**

```
{{firstName}} — last thought on this.

The biggest risk in event air isn't the initial booking — it's what happens between booking and the event. Name changes pile up. Attendees drop out and new ones register. Airlines change schedules. Group blocks expire.

Most teams either manage this in a spreadsheet (risky) or rely on an agency that treats it like regular travel (not the same thing).

We built our group management process specifically around this problem. Detailed air manifests, real-time tracking, and a dedicated agent who owns the entire event from first booking to last landing.

If you've got an event on the horizon and want to see how we'd handle the air logistics, I'm happy to walk you through it. No commitment — just 15 minutes.

[INSERT CALENDLY LINK]

Xavier Phillips
Nuvaio Travel | nuvaiotravel.com
975-444-0066
```

---

### Email 4 — The Breakup (Day 15)

**Subject line:** (same thread)

**Body:**

```
Hi {{firstName}},

I've sent a few notes about Nuvaio's group air travel services and haven't heard back — no worries at all, I know event season keeps you buried.

I'll leave the door open: if you've got a conference, incentive trip, or group event coming up and want a second set of eyes on the air logistics, we're here.

xavier@nuvaiotravel.com | 975-444-0066

Best,
Xavier
```

---

## CAMPAIGN 3: PARTNERSHIP OUTREACH

**Target:** HR Consultants, Benefits Brokers, Corporate Event Planners, DMCs, Relocation Companies — people who serve your same buyer but don't compete with you.

**Campaign name in Instantly:** `Nuvaio — Partnerships — [Month]`

---

### Email 1 — The Partnership Opener (Day 1)

**Subject line:**
- `Potential referral partnership?`

**Body:**

```
Hi {{firstName}},

I run a corporate travel consultancy called Nuvaio Travel — we handle air bookings, travel program management, and group event air logistics for mid-size companies.

I came across {{company}} and it looks like we serve a similar client profile but in non-competing ways. I'm reaching out because I think there could be a natural referral relationship between what you do and what we do.

Would you be open to a quick 15-minute call to see if there's overlap? No pitch — just exploring whether it makes sense to refer to each other when the opportunity comes up.

Xavier Phillips
Nuvaio Travel
975-444-0066
```

---

### Email 2 — The Follow-Up (Day 5)

**Subject line:** (same thread)

**Body:**

```
Hi {{firstName}},

Following up briefly. The reason I think there's a fit: your clients at {{company}} likely travel for business or host events, and when that comes up, having a trusted travel partner to refer them to makes you more valuable — not less.

On our end, we regularly talk to companies that need [HR consulting / benefits support / event planning / relocation services] and we'd love to have a go-to partner to send them to.

Happy to do a quick Zoom or phone call whenever works. Here's my calendar: [INSERT CALENDLY LINK]

Xavier
```

---

### Email 3 — The Breakup (Day 12)

**Subject line:** (same thread)

**Body:**

```
{{firstName}} — I'll keep this short. If a referral partnership isn't the right fit for {{company}} right now, no problem at all.

If it ever makes sense down the road, I'm easy to find. Wishing you a strong year.

Xavier Phillips
Nuvaio Travel | nuvaiotravel.com
```

---

## A/B TESTING STRATEGY

Instantly lets you A/B test subject lines. Here's how to use it:

**What to test first:** Subject lines on Email 1 only. This is where open rates live. Run each A/B test with at least 50 sends per variant before drawing conclusions.

**Subject line principles that work for cold email:**
- Questions outperform statements (by ~15% on average)
- Using {{company}} in the subject line boosts open rates (it looks personal)
- Lowercase, conversational subjects outperform formal/title-case subjects
- Keep it under 6 words
- Never use words like "free," "offer," "deal," "discount" — spam filters kill these

**Good subject lines to test:**

| Campaign | Variant A | Variant B |
|---|---|---|
| Corporate | `Quick question about {{company}}'s travel` | `{{firstName}}, how does {{company}} handle travel?` |
| Corporate | `Corporate travel at {{company}}?` | `Thought about {{company}}'s travel program` |
| Event | `Group air for {{company}}'s events?` | `{{firstName}} — question about event air logistics` |
| Event | `Who handles air for {{company}}'s conferences?` | `Air logistics for your next event` |

---

## LEAD LIST BUILDING — WHERE TO FIND CONTACTS

### For Corporate Travel Targets

**LinkedIn Sales Navigator (free 30-day trial, then $80/month):**
- Filter by: Title contains "Office Manager" OR "Director of Operations" OR "VP Finance" OR "Travel Coordinator" OR "Chief of Staff"
- Company headcount: 51–500
- Industry: Consulting, Construction, Energy, Professional Services, Technology, Pharma, Financial Services
- Geography: Start with your metro area, then expand to your state, then nationwide

**Apollo.io (free tier — 50 email credits/month):**
- Same filters as above
- Exports directly to CSV with email addresses
- Upgrade to $49/month if you need more credits — worth it

**Hunter.io (free tier — 25 searches/month):**
- Use for finding specific emails when you have a name and company domain
- Enter the company domain, it shows you the email pattern (e.g., first@company.com)

### For Event/Group Travel Targets

**LinkedIn:** Search for "Meeting Planner," "Event Coordinator," "Conference Director," "Incentive Travel Planner"

**PCMA and MPI member directories:** Both organizations have searchable directories of meeting professionals

**Cvent Supplier Network:** Event planners list their upcoming events here

**Industry conference websites:** Find the "Contact" or "About" page for upcoming 2026 conferences — the organizer is your target

### For Partnership Targets

**LinkedIn:** Search for "HR Consultant," "Benefits Broker," "Corporate Event Planner," "Relocation Specialist" in your metro area

**Alignable.com:** Free B2B networking platform — search for complementary businesses near you

---

## CAMPAIGN LAUNCH CHECKLIST

Before you hit "Start Campaign" in Instantly, verify:

- [ ] Secondary domain purchased and DNS records (SPF, DKIM, DMARC) configured
- [ ] Email warm-up has been running for 14+ days
- [ ] Calendly link created and inserted in Email 3 (and Email 2 of event campaign)
- [ ] CSV lead list uploaded with all personalization fields filled (no blank {{company}} fields)
- [ ] Sending window set to 8:00 AM – 11:30 AM recipient's timezone
- [ ] Daily send limit set to 15 (increase after 2 weeks)
- [ ] "Stop on reply" enabled
- [ ] Link tracking OFF (protects deliverability)
- [ ] Open tracking ON
- [ ] A/B test enabled on Email 1 subject lines
- [ ] Your email signature matches: Xavier Phillips | Nuvaio Travel | 975-444-0066

---

## WHAT TO DO WHEN THEY REPLY

**Positive reply ("Sure, let's talk"):**
Respond within 2 hours. Send your Calendly link or suggest 2–3 specific times. Keep it short: "Great to hear from you, {{firstName}}. Here are a few times that work this week: [times]. Or grab whatever works here: [Calendly link]. Looking forward to it."

**Interested but not now ("Timing isn't right"):**
Add them to a follow-up list. Respond: "Totally understand. I'll circle back in [60/90 days] — in the meantime, if anything changes, you know where to find me." Then set a reminder to re-engage in 2–3 months.

**Question ("What do you charge?" / "Can you handle X?"):**
Answer the question directly and bridge to a call: "Great question. [Brief answer]. It really depends on your specific travel volume and routes — the best way to give you an accurate picture would be a quick 15-minute call. Want to grab time this week?"

**Not interested ("We're all set"):**
Respond graciously: "Appreciate you letting me know, {{firstName}}. If anything changes down the road, don't hesitate to reach out. All the best to you and the team at {{company}}." Then remove them from future campaigns. Never argue or re-pitch.

**No reply after full sequence:**
Wait 90 days, then add them to a new campaign with a different angle. Don't send the same sequence twice.

---

## WEEKLY METRICS TO TRACK

| Metric | Target | Where to Find |
|---|---|---|
| Emails sent per week | 75–100 | Instantly dashboard |
| Open rate | 50%+ | Instantly dashboard |
| Reply rate | 5–10% | Instantly dashboard |
| Positive reply rate | 2–5% | Manual tracking |
| Calls booked per week | 2–3 | Calendly |
| Proposals sent per month | 3–5 | Manual tracking |

If your open rate drops below 40%, your subject lines or deliverability need work. If your open rate is strong but reply rate is under 3%, the email body needs reworking. The metrics tell you exactly where to focus.
