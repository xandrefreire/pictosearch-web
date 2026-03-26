# PictoSearch Website

Landing page, support page, and privacy policy for [PictoSearch](https://apps.apple.com/app/pictosearch) — a free AAC pictogram search app for iOS.

## Setup

1. Push this repo to GitHub as `pictosearch-gh-website`
2. Go to **Settings > Pages** and set source to `main` branch, root folder
3. The site will be available at `https://xandrefreire.github.io/pictosearch-gh-website`

## Required Images

Before deploying, add these files to the `images/` directory:

- `images/app-icon.png` — App icon (recommended 512x512)
- `images/app-store-badge.svg` — Download on the App Store badge ([download from Apple](https://developer.apple.com/app-store/marketing/guidelines/))
- `screenshots/01-search.png` — Search screen screenshot
- `screenshots/02-customizer.png` — Customizer screen screenshot
- `screenshots/03-onboarding.png` — Onboarding screen screenshot
- `screenshots/04-settings.png` — Settings screen screenshot

## Pages

- `index.html` — Landing page with features, screenshots, pricing
- `support.html` — Support center with FAQ and contact
- `privacy-policy.html` — Privacy policy

## Update App Store Link

Replace all `href="#"` placeholders with your actual App Store URL once the app is published.
