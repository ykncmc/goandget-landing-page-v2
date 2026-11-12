# Go&Get Landing Page

A responsive static landing website for Go&Get by Inquisyx Innovations Private Limited.

## Included
- `index.html` – landing page structure and SEO/social metadata
- `styles.css` – responsive visual design and animations
- `script.js` – navigation, scroll reveal and progress indicator
- `assets/` – supplied Go&Get logo, app screenshots and Open Graph preview image

## Deploy with GitHub + Vercel
1. Extract `goandget-landing-page.zip`.
2. Open your existing GitHub repository (or create a new one).
3. Upload the contents of the extracted folder, not the ZIP file itself.
4. Ensure `index.html`, `styles.css`, `script.js` and `assets/` are in the repository root.
5. In Vercel, import the repository or connect the existing project to it.
6. For this static site, use Framework Preset: **Other**. Leave Build Command and Output Directory empty; Vercel will serve the static files from the root.
7. Deploy.

## Before publishing
- Confirm `https://goandget.app/` is the intended canonical website URL. If your final domain is different, replace the canonical URL and `og:url`, `og:image`, and Twitter image URLs in `index.html` with the final domain.
- The Open Graph image is `assets/og-image.jpg`, created using the supplied Go&Get logo.
- App Store, Play Store and Instagram links are already configured.
- The AI demand/savings intelligence section is explicitly labelled as a future vision.
- Reservation is described as a customer request that a merchant can accept or reject.

## Version 2 visual refinements
- Removed the additional CSS phone/device frames around screenshots; the original device bezel already present in each screenshot is retained.
- Replaced generic platform marks with Android, Apple and Instagram SVG icons.
- Adjusted screenshot mockup dimensions to preserve the full portrait screenshots without cropping.

## Version 3 visual refresh
- Updated the website to a more vibrant, celebratory palette with warm, colorful section backgrounds and animated ambient halos.
- Removed the flat rectangular backdrops around the supplied phone mockup images using transparency, while retaining the enclosed app screens and phone bezels.
- Added soft drop shadows so the devices sit naturally within the page rather than appearing pasted on.

## Version 3.1 mockup refinement
- Removed the opaque white backing from the hero phone image wrappers.
- Kept phone mockups transparent and used subtle drop shadows for natural blending.
- Trimmed the colour spill around the customer offer mockup while retaining the phone and app screen.

## Version 4 — transparent screenshot integration
- Replaced the six customer/shop mockup assets with the newly supplied transparent PNG screenshots.
- Each of the six app screenshots is referenced exactly once in the landing page.
- Removed app screenshots from the hero area and introduced a unique animated Go&Get shopping illustration, avoiding repeated mockups.
- Presented the customer screens as a three-screen gallery and the shop screens as a two-screen gallery; the shop QR screen remains in its dedicated QR section.
- Kept the original screenshots' transparent canvases and phone bezels; no additional device borders or rectangular backing panels are added.
- Refreshed the SEO descriptions to describe nearby offer discovery and reservations accurately.
