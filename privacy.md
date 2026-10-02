---
title: Fitcore — Privacy Policy
permalink: /privacy
---

# Fitcore — Privacy Policy / Политика конфиденциальности

**Last updated: October 2, 2026**

Developer / Разработчик: **ZackysStudio**
App / Приложение: **Fitcore — workout & nutrition tracker**
Contact / Контакты: **support.zackysstudio@gmail.com**

This Privacy Policy explains how **Fitcore** ("the App", "we", "us"), published by
**ZackysStudio**, handles information when you use the App. The App is a workout planning,
nutrition tracking and AI fitness assistant app for a general audience. **It is not directed
to children under 16** (or the equivalent minimum age in your country).

By creating an account and using the App you agree to this Policy.

---

## 1. Summary

- To use the App you create an account with an **email and password**, or by **signing in
  with Google**.
- Our server stores your **account and profile** (email, name, gender, date of birth/age,
  height, weight, activity level, experience level, goal) and your subscription status. The
  server is operated by us.
- Your **workout history, nutrition log, custom exercises, programs and AI chat history stay on
  your device**. They are not uploaded to our server and are not synchronized between devices.
- The **food-scanning**, **AI assistant** and **AI workout generation** features send your
  photos, messages and the profile details listed below, through our server, to
  **Google's Gemini API**.
- If you purchase **Premium**, it is billed through **Google Play / the App Store**, and the
  subscription status is confirmed through **RevenueCat**.
- Account confirmation emails are sent through **Resend**.
- To keep the free AI-scan limit fair, the App sends a **device identifier** to our server,
  which stores only a one-way hash of it.
- We do **not** sell your personal information, we do **not** show ads, and the App contains
  **no advertising, analytics or crash-reporting SDKs**.
- Data exchanged between the App and our server is protected **in transit by encryption
  (HTTPS/TLS)**, and passwords are stored **hashed**.

---

## 2. Information we and our providers process

### 2.1 Account data

When you register with an email and password, or sign in with Google, we process your
**email address**. Passwords are stored **hashed** and are never accessible to us in plain
text. If you sign in with Google, Google shares your **email, name and profile picture** with
our authentication service. Our authentication service also keeps technical **session records**
(session tokens and timestamps) so that you stay signed in.

### 2.2 Profile data stored on our server

So that your profile and subscription work on your account, our server stores: your **first
and last name**, **gender**, **date of birth / age**, **height**, **weight**, **body-fat
percentage** (if you enter it), **activity level**, **experience level** and **nutrition goal**;
your **Premium status and its expiry date**; and **usage counters** (how many AI scans, chat
messages and workout generations you have used in the current period, and when that period
started).

Body measurements and goals may be considered **health data**. We use them only to provide the
App's features (see sections 3 and 4).

### 2.3 Data stored only on your device

The following stays **on your device only** and is **not sent to our server**: your **workout
history and logged exercises**, **custom exercises**, **workout programs**, your **nutrition
log**, your **AI chat history**, your **calorie and macro targets** (calculated on the device),
your settings and your reminders. Because of this, this data is not available on another device,
and it is lost if you delete the App's data or uninstall the App.

Depending on your device settings, **Android may include the App's data in your Google backup**
and restore it when you reinstall the App. That backup is controlled by Google and your device
settings, not by us.

If you sign in with a different account on the same device, the previous account's local data is
set aside on the device and restored when you sign in to that account again. Deleting your
account removes this local data from the device (see section 7).

### 2.4 Photos and food scanning (Google Gemini API)

If you use the food-scanning feature, the photo(s) of your meal and any description you type are
sent to our server, which forwards them to **Google's Gemini API** to recognize the food and
estimate its calories and macros. **We do not store the photos** on our server; Google processes
them as described in section 2.6. See: https://ai.google.dev/gemini-api/terms

### 2.5 AI assistant and workout generation (Google Gemini API)

- **AI assistant (chat):** the message you send, up to the **last 20 messages** of the
  conversation, and a short profile summary needed to personalize the answer: your **name**,
  gender, age, height, weight, BMI, activity level, experience level, goal, daily calorie and
  macro targets, what you have eaten **today** (totals), the name of your active program and
  today's session, and your workout streak.
- **AI workout generation:** your goal, available equipment, training days per week, gender,
  age, height, weight, BMI, experience level and the list of exercise names available in the App.

This content is forwarded to **Google's Gemini API** to generate the response. **We do not store**
the content of your messages or generated programs on our server (your chat history is kept on
your device only).

### 2.6 How Google handles Gemini data

Google processes this content as an independent provider under the Gemini API terms. Those
terms differ between free-of-charge and paid usage; under the free-of-charge terms Google may use
submitted content to improve its products and it may be reviewed by people. Please do not put
information in photos or chat messages that you do not want processed this way. See:
https://ai.google.dev/gemini-api/terms

### 2.7 Food databases (Open Food Facts and USDA FoodData Central)

When you search for a food by name, the **search text** is sent **directly from your device** to
**Open Food Facts** (search.openfoodfacts.org) and/or **USDA FoodData Central**
(api.nal.usda.gov) to find nutrition values. These services receive the search text and your
**IP address**; they do not receive your account, name or email.

### 2.8 Subscriptions and purchases (RevenueCat & app store billing)

If you buy a **Premium** subscription, the transaction is handled by **Google Play Billing**
or the **App Store**. We use **RevenueCat** to validate and manage your subscription status.
RevenueCat processes a purchase token and an app-user identifier (our internal account ID) to
confirm whether your subscription is active. **We never receive or store your full payment card
details** — those are handled by the app store. See: https://www.revenuecat.com/privacy

### 2.9 Emails (Resend)

When you register, we send you a confirmation email (and, if you ask, a new confirmation link).
These emails are sent through **Resend**, which processes your email address and the message to
deliver it. We send **no marketing emails**. See: https://resend.com/legal/privacy-policy

### 2.10 Device identifier

To keep the free AI-scan limit fair — so that creating a new account does not give new free
scans — the App sends a **device identifier** with its requests (on Android, the device's
Android ID). Our server keeps **only a one-way (keyed) hash** of it, never the identifier itself,
together with the number of AI scans used on that device and when the counting period started.
While your account exists, we also record that it was used on that device; this link is removed
when the account is deleted.

### 2.11 Server and technical logs

Our server keeps a technical **request log**: the time, request type and address path, response
code, response time and size, your **IP address** and your **account ID**. The log does **not**
contain the content of requests — no photos, messages or tokens. Entries are **deleted
automatically after 14 days**. Our server is reached through **Cloudflare**, which processes
requests (including your IP address) in order to deliver and protect the service.

### 2.12 Fonts

The App may download its fonts from **Google Fonts** the first time they are needed. This
reveals your IP address to Google; no account data is sent.

### 2.13 Local reminders and notifications

The App can schedule reminders about workouts and meals at times you choose. These reminders
are scheduled **entirely on your device** using the device's own notification system; no
reminder content or schedule is sent to us.

---

## 3. How we use information

We (and our providers, for their own described purposes) use the information to:

- create and operate your account and keep you signed in;
- store your profile and calculate personalized targets;
- power the photo-based food recognition feature, the AI assistant and AI workout generation;
- process and validate your Premium subscription;
- send you account confirmation emails;
- apply usage limits, keep the service secure, prevent abuse and provide customer support.

We do **not** sell your personal information, and we do **not** use your data for
advertising.

---

## 4. Legal bases (EU/UK users)

- **Contract** — to create your account and provide the App's features you ask for.
- **Consent** — for health-related profile data and for sending your photos and messages to
  Google's Gemini API. You give it when you accept this Policy and use those features, and you
  can withdraw it at any time by stopping to use the features or by deleting your account.
- **Legitimate interests** — to keep the service secure, apply usage limits and prevent abuse
  (technical logs, device identifier).
- **Legal obligation** — where we must keep or disclose information by law.

---

## 5. Permissions the App requests

- **Internet** — to sign in, sync your profile and use the online features described above.
- **Camera and photo library** — to take or select a photo of your food for the scanning
  feature.
- **Notifications** — to show you the reminders you schedule.
- **Exact alarms** (`SCHEDULE_EXACT_ALARM` on Android) — so reminders you schedule fire at the
  exact time you chose, including while the device is idle.
- **Boot completed** — so your scheduled reminders are re-armed after your device restarts.
- **Vibration** — for haptic feedback.

---

## 6. Data sharing

We share data only with the providers below, and only as needed to provide the App's features:

| Provider | What it receives | Why |
| --- | --- | --- |
| **Google (Gemini API)** | Photos, messages and profile details described in 2.4–2.5 | Food recognition, AI assistant, workout generation |
| **Google (Sign-In)** | Your Google account details if you choose Google sign-in | Sign-in |
| **Google (Fonts)** | Your IP address | Download app fonts |
| **RevenueCat** and **Google Play / App Store** | Purchase token, account ID, subscription status | Premium subscriptions |
| **Resend** | Your email address and the confirmation message | Account emails |
| **Cloudflare** | Requests to our server, including IP address | Delivering and protecting our server |
| **Open Food Facts**, **USDA FoodData Central** | Food search text and IP address (directly from your device) | Nutrition values |

Our database and backend run on infrastructure that we operate directly rather than on a
third-party cloud database provider. We do not use advertising or analytics SDKs.

We may also disclose information if required by law. We do **not** sell your personal
information.

---

## 7. Data retention and deletion

We keep your account and profile data while your account is active.

**You can delete your account yourself in the App:** open the **Profile** tab, scroll to the
bottom and tap **Delete account**, then type the confirmation word and confirm. Deletion is
immediate. You can also request deletion by email — see our
[Data Deletion page](delete) or write to **support.zackysstudio@gmail.com**.

When your account is deleted, we remove: your sign-in account and sessions, your profile and
subscription status, your usage counters, the request-log entries linked to your account, and we
ask RevenueCat to delete your subscriber record. The App's data on your device is erased too.

A few things remain, as described on the [Data Deletion page](delete): a short **record that the
deletion happened** (date, technical account ID, masked email and IP address) kept for security
and accountability; the **device scan counter** (linked to a hash of the device, not to your
account); records that app stores and payment providers must keep by law; and data held by the
providers named above under their own policies. Deleted data may also remain for a short time in
routine technical backups of our server until they are overwritten.

Deleting your account does **not** cancel an active Google Play / App Store subscription — cancel
it separately in your store account.

---

## 8. Your rights

Depending on where you live (for example under the EU/UK GDPR or the CCPA), you may have the
right to access, correct, delete, or restrict processing of your personal data, to object to
certain processing, to withdraw consent, or to receive your data in a portable format. You can
delete your account in the App (section 7). To exercise other rights, contact us at
**support.zackysstudio@gmail.com**. You also have the right to complain to your data-protection
authority (in the Czech Republic: the Office for Personal Data Protection, https://www.uoou.gov.cz).

---

## 9. International transfers

Our servers and providers may process data in countries other than your own, including the
United States. Where required, transfers rely on appropriate safeguards under the providers' own
frameworks (for example, standard contractual clauses or the EU–US Data Privacy Framework).

---

## 10. Children

The App is intended for a **general audience and is not directed to children** under the age
of 16 (or the applicable age in your jurisdiction). We do not knowingly collect personal
information from children. If you believe a child has provided us personal information,
contact us at **support.zackysstudio@gmail.com** and we will take appropriate steps.

---

## 11. Medical disclaimer

The App is **not a medical device** and the health, nutrition and workout information it
provides — including AI assistant responses — is for **general informational purposes only**
and is **not medical advice**. Consult a qualified physician before starting any exercise
program or changing your diet.

---

## 12. Changes to this Policy

We may update this Policy from time to time. Material changes will be reflected by updating
the "Last updated" date above and, where appropriate, through an in-app notice.

---

## 13. Contact

**ZackysStudio**
Email: **support.zackysstudio@gmail.com**
