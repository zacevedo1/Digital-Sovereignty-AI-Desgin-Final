# Design Direction

## Project Mood
The site must feel like an authoritative, grassroots tactical command center. It needs the seriousness of a legal defense dossier combined with the frictionless learning experience of an interactive educational tool. It is unapologetic, raw, and designed for gaining attention strategically. 

## Visual Keywords
Tactical, Authoritative, High-Contrast, Bold Maximalism, Grunge, Unredacted.

## Color Direction
The palette relies on absolute contrast to highlight corporate extraction and community vulnerabilities.
*   **Background Canvas:** `#0D0F12` (Deep Obsidian Void)
*   **Base Text & Borders:** `#F0F4F8` (High-Visibility Off-White)
*   **Active Legal Tools / Verification:** `#00FF66` (Terminal Phosphor Green)
*   **Threat Alerts (Grid/Water):** `#FFB700` (Warning Amber)
*   **Critical Violations / NDA Exposures:** `#FF3333` (Tactical Crimson)

## Typography Direction
*   **Headings & Display:** `Archivo Black`, sans-serif. Used for all massive section titles and warnings. This typeface must dominate the visual space.
*   **Body Text:** `Elza Text`, sans-serif. Used for all educational data, step-by-step guides, and interface labels. It must remain highly legible at smaller scales.

## Layout Direction
The layout must utilize **Progressive Disclosure**. Because the target audience knows very little about AI infrastructure, the interface cannot dump all the information at once. It should use step-by-step timeline cards, accordions for legal deep dives, and compartmentalized grid sections with stark, solid borders.

## Image / Media Direction
I explicitly reject the use of AI-generated images. The site will exclusively feature real-world, verified photography. This includes actual photos of data center interiors, cooling towers, and documented physical impacts on local communities to ground the academic data in raw reality.

## References
*   CodeX / Interactive terminal interfaces (for clean inputs and data tables).
*   Grassroots advocacy and whistleblower document drops (for raw, unredacted layouts).
*   Khan Academy (for progressive learning modules).

## Avoid
*   "Disruptive" or chaotic styling that harms readability.
*   Wall-of-text information dumps.
*   AI-generated artwork or generic tech startup illustrations.

## Notes for the Coding Agent
1.  **Level Up Concept (Typography Performance):** When importing Archivo Black, append `&display=swap` to the Google Fonts URL to ensure the text renders immediately while the font file downloads.
2.  **Level Up Concept (Readability):** Set the `max-width` of all `<p>` tags using the `ch` unit (e.g., `max-width: 65ch;`) to ensure frictionless reading lengths.
3.  **Responsive Scale:** Use the CSS `clamp()` function for all `Archivo Black` headings so the maximalist typography scales perfectly from mobile to desktop.
4.  **Structure:** Use a CSS Grid architecture to compartmentalize the layout. Do not use soft drop shadows or rounded corners. Keep borders sharp, solid, and high-contrast.