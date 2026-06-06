# Privacy Policy

**Effective date:** 2026-06-10
**App:** Stamp Collector
**Operator:** Withawat Chotprom, Denmark
**Contact:** withawat.chotprom@gmail.com

This Privacy Policy describes how Stamp Collector ("we", "us", "the app") collects, uses, stores, and discloses information when you use the app on iOS and Android. By using the app you agree to this policy. If you do not agree, please do not use the app.

We have written this in plain language. If anything is unclear, contact us at the email above and we will explain.

---

## 1. What this app does

Stamp Collector lets you photograph postage stamps and identify them with an AI vision model, then catalog them in a personal collection on your phone. A free tier ("Collector") gives you 20 AI scans per month and stores your collection locally on the device. A paid tier ("Collector Plus") gives you 200 AI scans per month, richer scan results (catalog numbers, historical context), and cloud backup that lets your collection survive a phone reset or move to a new device.

Some features require you to sign in with a free account (email + password). Others (browsing your collection, manually adding stamps, exporting/importing your collection as JSON) work without an account.

## 2. Information we collect

We collect the minimum information needed to run the app. We **do not sell your personal data** to anyone.

**a) Information you provide directly**

- **Email address and password** (if you create an account). Required only for the AI scan feature and for cloud backup on the paid tier. Browsing, manual entry, and export/import work without an account.
- **Stamp photographs** that you choose to scan. These photos are processed by our AI provider (see Section 3) for identification.
- **Stamp metadata** that you enter manually (e.g., notes, condition, quantity, value estimates you override).

**b) Information collected automatically**

- **Device identifiers** (advertising ID on Android, IDFA on iOS) used only by the ad-serving feature on the free tier, and only with your consent where required.
- **App usage signals** needed to enforce your monthly scan quota (the number of scans you have made this month, the current month). Stored on our servers against your account.
- **Crash and error data** if you encounter an issue. We do not currently use a crash reporting service, but if we add one before launch this policy will be updated to name the provider.

**c) Information we do NOT collect**

- We do not access your contacts, location, microphone, calendar, SMS, or call logs.
- We do not read photos from your camera roll except those you explicitly select to import.
- We do not use cookies (this is a mobile app, not a website).

## 3. Third parties who process data on our behalf

We use a small set of third-party services to run the app. Each one only receives the minimum data it needs, and each has its own privacy policy linked below.

| Service | What we send to them | Why | Their policy |
|---|---|---|---|
| **Anthropic** (Claude API) | The stamp photo you scan, for AI identification. The photo is sent through our own server, never directly from your phone with your account attached. | To identify the stamp in your photo. | https://www.anthropic.com/legal/privacy |
| **Supabase** (backend infrastructure, EU region — Paris) | Your account email, encrypted password, scan-quota count, and on the paid tier your stamp collection metadata and photos. Servers are located in the European Union. | Account login, server-side scan quota enforcement, and Collector Plus cloud backup. | https://supabase.com/privacy |
| **RevenueCat** (subscription management) | An anonymized identifier tied to your account, the subscription status (free/Collector Plus), and the receipt from Apple or Google's billing system. | To verify and synchronize your subscription across devices. RevenueCat does not receive your payment details — those stay with Apple or Google. | https://www.revenuecat.com/privacy |
| **Google AdMob** (free-tier ads only) | Your device's advertising identifier, ad interaction events (impressions, clicks, dismissals), and your approximate region based on IP address. | To show ads on the free tier and report ad performance. Paid users see no ads and no data flows to AdMob from their device. | https://policies.google.com/privacy |
| **Apple App Store / Google Play Store** | Your payment details (handled entirely by Apple or Google — we never see your card details), subscription status. | To process your subscription if you upgrade to Collector Plus. | Apple: https://www.apple.com/legal/privacy/ — Google: https://policies.google.com/privacy |

We do not share data with any third party for advertising or marketing purposes outside the AdMob flow described above.

## 4. How we use the information

- To identify your stamps using AI (Anthropic).
- To authenticate you and let you access your account (Supabase).
- To enforce the monthly scan quota and prevent abuse (Supabase).
- To back up your collection in the cloud if you have Collector Plus (Supabase).
- To verify your subscription status (RevenueCat).
- To serve ads to free-tier users (AdMob), subject to your consent where required.
- To contact you about your account, security issues, or important changes to this policy.

We do not use your data for any other purpose without your consent.

## 5. Your rights

You have the right to access, correct, export, and delete your data at any time.

- **Delete your account.** Settings → Account → Delete my account. This permanently deletes your account login and all server-side data (cloud backups, profile, scan-quota record). Your local stamp collection on the device is not deleted by this action — you can choose to keep it on the device or uninstall the app. Deletion is permanent and cannot be undone or recovered.
- **Export your data.** Settings → Export collection (JSON). You receive a file with every stamp in your collection.
- **Request a copy of your data we hold** (under GDPR Art. 15). Email us at the contact address above and we will provide a copy within 30 days.
- **Correct or restrict** how your data is processed. Email us.
- **Object to processing** for ads (free tier). You can revoke ad consent on Android in Settings → Apps → Stamp Collector → Permissions, or by uninstalling the app. The consent prompt also reappears periodically.
- **Lodge a complaint** with your local data protection authority. In Denmark, that is Datatilsynet (https://www.datatilsynet.dk).

## 6. Data retention

- **Account data** (email, password hash, profile row): retained until you delete your account.
- **Cloud-backed collection data** (Collector Plus): retained until you delete it from the app or delete your account.
- **Stamp photos sent to Anthropic for identification**: Anthropic does not retain inputs sent through their API by default; the photo exists only for the duration of the API call.
- **Local stamp collection** (on your device): retained until you uninstall the app or wipe your device. We have no copy.
- **Ad event data** (AdMob): retained by Google per their policy; we do not retain a copy.

## 7. Children's privacy

This app is not intended for children under 13 (or under 16 in EEA countries that have set the GDPR age of digital consent higher). We do not knowingly collect personal information from children. If you believe a child has provided personal information to us, please contact us and we will delete it.

## 8. International data transfers

Our backend (Supabase) is hosted in the European Union (Paris region). However, some sub-processors are located outside the EU:

- **Anthropic** is based in the United States. Photos sent for identification are transmitted to Anthropic's US infrastructure for processing.
- **RevenueCat** is based in the United States.
- **Google (AdMob)** processes ad data globally.
- **Apple** and **Google Play** operate globally.

Where required, we rely on Standard Contractual Clauses or equivalent legal mechanisms approved by the European Commission for these transfers. If you are not comfortable with US data transfers, you can avoid most of them by (a) not using the AI scan feature (which avoids Anthropic), (b) using the free tier without cloud backup (which avoids RevenueCat), and (c) declining ad personalization or not using the free tier (which limits AdMob data).

## 9. Security

We use industry-standard security measures including HTTPS for all network traffic, password hashing, row-level security on the database, server-side scan-quota enforcement, and signed binaries for the app. No system is perfectly secure; we cannot guarantee that data will never be exposed.

If we discover a breach affecting your data, we will notify you and the relevant data-protection authority within 72 hours as required by GDPR.

## 10. AI scan accuracy

The AI scan feature provides an automated identification and an estimated value. **These are best-effort suggestions, not professional appraisals.** The value shown is for general reference only and should not be used for insurance, tax, sale, or investment decisions. Always consult a qualified philatelist or auction house for binding valuations.

## 11. Changes to this policy

We may update this Privacy Policy as the app evolves. The "Effective date" at the top will change. For significant changes (e.g., new third parties, new data we collect), we will notify you in the app or by email before the change takes effect.

## 12. Contact

Questions, requests, or complaints about this policy:

**Email:** withawat.chotprom@gmail.com

---