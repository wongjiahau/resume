# Wong Jia Hau

hou32hou@gmail.com - [github.com/wongjiahau](github.com/wongjiahau) - Kuala Lumpur, Malaysia

---

## Summary

Enthusiastic about improving the developer's experiences, and also low-level system programming.

Full-stack software engineer with 6+ years of experience spanning ERP systems, AI applications, and developer tooling.

Built end-to-end type-safe systems, experimented with programming languages, and solving hard integration problems at the systems level.

Strong background in Rust, TypeScript, React and Python, with a track record of delivering production systems solo and leading small teams.

---

## Experience

### Full-stack Software Engineer @ [Exec](https://www.exec.com/)

_July 2024 – March 2026_

- Built and maintained playback video generation of roleplays, featuring real-time AI avatar integration with Tavus
- Engineered a video composition pipeline using FFmpeg to composite live webcam feeds with Tavus AI avatar streams, PDF file sharing, and screen sharing, and resolved audio-video sync issues
- Developed Django/React full-stack features including webcam stream management (pausable webcam with canvas compositing, Loom-style recording uploading chunks to AWS S3)
- Wrote **AST-based codemods using [LibCST](https://github.com/Instagram/LibCST)** to systematically refactor the Python/Django codebase for improved type-checkability (specifically making `Service` classes type-safe, both at declaration sites and call sites)

---

### Full-stack Software Engineer @ [Grace (Catholic AI iOS App)](https://apps.apple.com/my/app/grace-catholic-companion/id6478172934)

_July 2023 – July 2024_

- Sole engineer (alongside a product designer and UI/UX designer) responsible for the entire stack: Django backend, SwiftUI frontend, and infrastructure on Render
- Built a user memory system inspired by academic research, predating the mainstream adoption of memory in LLM applications, featuring:
  - **Archival memory:** long-term storage in Postgres, retrieved on demand via OpenAI embeddings
  - **Working memory:** a rolling summary of recent messages plus persistent user traits (name, gender, relationships, current challenges, etc.)
- Built a periodic message summarization pipeline to support infinite-length conversations
- Delivered the full product from foundation (built by another engineer) to production independently
- Used Nix and Docker to unify development, CI, and deployment environments
- Built a cronjob to generate daily bible verses images via OpenAI

---

### Full-stack Software Engineer @ [Didian](https://mydidian.com/)

_2019 – July 2023 (~5 years)_

- Developed full-stack ERP applications almost from scratch using Node.js, TypeScript, GraphQL, PostgreSQL, MongoDB and AWS
- Built client-facing dashboards and internal-facing dashboards for managing property transactions
- Executed a gradual **zero-downtime migration** of a large portion of the database from MongoDB to PostgreSQL
- Introduced and enforced Test-Driven Development (TDD) culture to the team
- Built a **custom AST refactoring tool** using the TypeScript ESLint parser to systematically ensure GraphQL query/mutation names follow a specific naming scheme
- Built an internal **GraphQL backend type codegen tool** that generates TypeScript type declarations for backend resolvers from `.graphql` schema files, filling an ecosystem gap (no backend equivalent of GraphQL Code Generator existed at the time), completing **end-to-end type safety** from database through resolvers to the React frontend
- Led two interns in building a **PDF form field mapping editor**, a visual tool allowing users to draw field regions on uploaded PDFs and map database records to those fields
- Reverse-engineered a mobile app's private API (via decompilation) to enable live property price chart scraping from a developer with no public API
- Reverse-engineered a proprietary FirebirdDB schema from the Malaysian SQL Accounting system's blob files to enable accounting data integration with no official documentation
- Migrated the entire development, CI, and production environment to **Docker**, eliminating environment inconsistency issues across the team
- Built multilpe analytical dashboards using Holistics by integrating it with the company's databases
- Led and trained over 10 interns
- Invited a few times to give talks regarding software engineering in UTAR

---

## Open Source & Projects

### [Ki Editor](github.com/wongjiahau/ki-editor)

- Not just a mere improvements over existing TUI modal editors like Neovim, Kakoune or Helx, but a total revamp from the ground-up, resulting in
  a highly consistent mental model and ergonomic keymaps
- Written in Rust, featuring LSP integration, Kitty Keyboard Protocol support, fuzzy matching (nucleo), file explorer, file picker, global search and etc.
- Heavy usage of Rust mpsc channels for async tasks
- Been using it personally for all kinds of work (since Didian) since it was bootstrapped with Neovim around 2 years ago
- Coordinated the community using Zulip
- This resume is edited with Ki

---

### [TTAP: Timetable Arranging Program](github.com/wongjiahau/ttap-web)

- TTAP was built to solve a major pain point of arranging timetables for the next trimester, caused by the combinatorial explosion of valid timetables given the vast array of available slots
- Built a timetable scheduling web app (React, TypeScript, Redux) widely and actively adopted by UTAR students each semester, accumulating 37k+ total downloads across all platforms since 2018
- Developed and optimized a depth-first search algorithm that runs efficiently even in the browser JavaScript runtime
- Won PROCOM 2018 (Software Programming Innovation Competition): 1st place among 13 Malaysian universities, awarded RM5000 cash prize
- Represented Malaysia at KOSEN PROCON, Tokushima, Japan (Oct 2018), an international competition running since 1990, and became the only international team to win the Toshiba Enterprise Prize

References:

- [https://news.utar.edu.my/awards/2018/76/76.html](https://news.utar.edu.my/awards/2018/76/76.html)
- [https://news.utar.edu.my/awards/2018/48/48.html](https://news.utar.edu.my/awards/2018/48/48.html)

---

### [Keli Language](github.com/KeliLanguage/compiler) (Final Year Project)

Designed and implemented a programming language that is meant to improve readability and writeability from scratch, featuring:

1. Parser written with parsec
2. Type-checking with partial type inference
3. LSP features: auto-complete and diagnostics

### [Material Design in Xaml Toolkit](https://github.com/MaterialDesignInXAML/MaterialDesignInXamlToolkit)

Pioneered [a project](https://github.com/MaterialDesignInXAML/MaterialDesignInXamlToolkit/pull/765) that shows the corresponding code of each components in the demo app.

---

## Skills

| Aspect         | Tools                                                    |
| -------------- | -------------------------------------------------------- |
| Languages      | Rust, Haskell, TypeScript, Python, JavaScript, SQL       |
| Frontend       | React, SwiftUI                                           |
| Backend        | Django, Node.js, GraphQL                                 |
| Infrastructure | Docker, Nix, GitHub Actions, Gitlab CI/CD                |
| Databases      | PostgreSQL, MongoDB                                      |
| AI/ML          | LLM integration, memory systems, Tavus, Vapi, ElevenLabs |
| Tools          | LSP protocol, transpiler, parsers, FFMPEG, TUI editor    |

---

## Education

Bachelor of Software Engineering: Distinction (3.8+)

Universiti Tunku Abdul Rahman (UTAR), Sungai Long. Graduated 2019.
