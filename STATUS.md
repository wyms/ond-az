# OND Scottsdale 2026 — Project Status

## Event Overview
- **Event:** Old Not Dead (OND) Scottsdale 2026
- **Dates:** February 14-15, 2026
- **Location:** Scottsdale Ranch Park, E. Via Linda, Scottsdale, AZ
- **Website:** https://wyms.github.io/ond-az/
- **Repo:** https://github.com/wyms/ond-az

## Day 1 — Saturday, Feb 14: King of the Beach (COMPLETE)
- **Format:** KOB — partner with every player in your pool
- **Players:** 42 across 10 pools on 6 courts
- **First Serve:** 8:30 AM
- **Pool Play:** 8:30 AM – 12:00 PM
- **Bracket:** Single elimination starting 12:30 PM

### Championship Results
- **Eagle Bracket (Championship):** Kyle & Steve defeated Kris & Jeff
- **Hawk Bracket (Consolation):** Angelo & Dan defeated Doc & Bruce
- Photos posted: Eagle Champions, Eagle Finals, Hawk Champions, Hawk Finals

## Day 2 — Sunday, Feb 15: Bring Your Partner (IN PROGRESS)
- **Format:** BYOP — sign up with your doubles partner
- **Teams:** 17 teams across 4 pools
- **Courts:** TBD
- **First Serve:** 9:30 AM
- **Scoring:** Rally scoring, games to 21, win by 2, cap 25
- **Bracket:** Single elimination starting ~1:00 PM

### Pools
| Pool | Teams |
|------|-------|
| Pool 1 (5 teams) | Kyle & Wayne (109), Blake & Jon (96), Devon & Randy (111), Scott P. & Rick K. (115), Bojan & Steve G. (109) |
| Pool 2 (4 teams) | Steve D. & David (105), Dar & Joe R. (108), James & Dan (115), Kent & Bryan (116) |
| Pool 3 (4 teams) | Alan & Steve S. (116), Joe L. & Mike (105), Joel & Nathan (108), Paul & Bruce (114) |
| Pool 4 (4 teams) | Kris & Chad (109), Scott H. & Omar (96), Angelo & Rob (129), Chris & John (120) |

*Numbers in parentheses = combined age (dino number)*

## Future OND Events
| Event | Date | Location | Website |
|-------|------|----------|---------|
| OND Austin | Apr 11-12, 2026 | ATX Beach, Austin, TX | https://wyms.github.io/ond-atx/ |
| OND Hermosa | Jul 2026 | Hermosa Beach, CA | TBD |
| OND Laguna | Sep 2026 | Laguna Beach, CA | TBD |

## Technical Details
- **Architecture:** Single-file HTML/CSS/JS (`index.html`)
- **Hosting:** GitHub Pages (main branch)
- **Day Toggle:** JavaScript `switchDay()` function shows/hides `#day1`/`#day2` divs
- **Hero Section:** Dynamic content via `heroData` object
- **Sticky Nav:** Appears after 350px scroll
- **Images:** 4 JPEG championship photos (~2-2.7 MB each) committed to repo
- **Fonts:** Google Fonts — Oswald, Bebas Neue, Barlow Condensed, Barlow
- **No build step** — edit index.html directly

## Key Constraints
- Do not push to GitHub without explicit user approval
- Names use first name only (last initial added only to disambiguate duplicates)
- Combined ages shown as "dino number" per team
- Pool sheets and game order managed by Scott (not on website)

## Known Issues / Notes
- Image files are large (2-2.7 MB each); consider compression for faster mobile loading
- Day 1 `#day1` div must be properly closed before Day 2 `#day2` div starts (past bug: nesting caused Day 2 to be invisible)
