# AGENTS.md — Rules for working on Wenhan Xue's site

Site: personal home page for Wenhan Xue (`index.html`), hosted via GitHub Pages at wenhanxue.github.io.
Source of truth for content: `XUE, Wenhan Resume.pdf` in this folder.

## Never publish
- Home address, date of birth, or any government/ID numbers.
- Phone number on the web page itself. Exception: Wenhan chose to publish the CV PDF as is, which includes the phone number. Ask before putting it anywhere else.
- Anything not in the CV or explicitly provided by Wenhan. No invented projects, metrics, quotes, testimonials, or links.
- Private interview/participant data from research projects (names, quotes, recordings, identifying details).
- Credentials, API keys, tokens, or private repo contents.
- Embedded trackers, analytics, or third-party scripts/fonts that send visitor data elsewhere.

## Ask first
- Before any `git push`, commit to a shared branch, deploy, or anything outward-facing. Default: local only.
- Before adding a new personal contact detail (including the email address if it changes) or social profile.
- Before changing facts: dates, GPA, titles, numbers, advisor names, or wording that changes the meaning of a CV line.
- Before adding or deleting pages/files beyond `index.html`, `AGENTS.md`, and the CV.
- Before reordering sections away from CV order, or removing any CV content.
- Before adding links I couldn't verify (e.g. Publications and Posters URLs).

## Style
- Tone: professional but casual. First-person-neutral, plain words, no buzzword stacking.
- Colors: A ux-friendly white as the main color, and light blue as an accent color, use additional colors as you see fit (e.g., for contrast, highlight, etc.), but DO NOT exceed three colors. Accessible contrast (WCAG AA).
- Layout: single page, section order matches the CV (Education, Experience, Academic Research, Additional Information). Tiles for scannability.
- Navigation: minimal — a sticky bar with one link per section plus LinkedIn and GitHub.
- Tech: plain HTML + CSS, no build step, no external dependencies. Mobile-friendly, supports dark mode, respects reduced motion.
- Content: keep CV wording faithful; light edits for web only (e.g. splitting into tiles).
- Accessibility: semantic headings, visible focus states, descriptive link text, `alt` text where images exist.
