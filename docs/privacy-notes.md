# Privacy notes — public-copy firewall

Checklist for anyone editing this repo or copying text from it onto portfolio, LinkedIn, or GitHub Pages.

## Hard no (do not add, link, or imply)

- [ ] IRB numbers (including #31816) or IRB protocol / consent materials
- [ ] Clinical framing, diagnoses, treatment language, or care claims
- [ ] Participant data, quotes, demographics that could identify people
- [ ] Raw field data, local `data/` trees, or analysis dumps
- [ ] Links to private `2050-landscape` (or similarly private landscape repos)
- [ ] Links or path references to private `jlzhao27` lab data locations
- [ ] Drive / cloud paths that hold IRB or participant stores
- [ ] Invented metrics, outcomes, publications, or Stealth / product connections

## Women2050 / ATHLETE

- [ ] Treat as **placeholder only** until the founder confirms what may appear publicly
- [ ] If unsure, omit the name rather than guessing

## What *is* OK here

- Role title: Undergraduate Research Assistant
- High-level group framing: Proactive Health Informatics (exact lab name still a placeholder until confirmed)
- Public **process** language the founder has cleared (methods habits, collaboration, tools — without field content)
- Explicit statements that this repo holds **no** dataset and makes **no** clinical claims

## Before every commit

1. `git status` — confirm nothing under `data/`, no `.env`, no spreadsheets slipped in
2. Diff the README — no IRB numbers, no private URLs, no participant detail
3. Prefer leaving placeholders over filling gaps with impressive-sounding guesses

## If something sensitive was committed by mistake

Do not “fix forward” by deleting in a new commit alone if the secret already pushed — rotate/remove per GitHub guidance and treat history as compromised until cleaned. Prefer stopping and asking before any history rewrite.
