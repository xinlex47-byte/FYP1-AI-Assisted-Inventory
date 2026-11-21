# AI-Assisted Inventory Efficiency for Automotive Spare Parts SMEs in Malaysia Using Barcode/QR Code Scanning and Storage Location Tracking

Final Year Project I · Bachelor of Information Technology · Raffles University (Faculty of AI & Robotics)

| | |
|---|---|
| Student | Lee Wen Xin |
| Supervisor | Ts Dr Yang Chee Beng |
| Semester | Year 2 / Semester 5 · November 2026 |

## Project summary

Small automotive spare parts shops often record stock on paper or in spreadsheets, which leads to inaccurate records (PS1), and staff cannot easily see how many units of a part are left or which shelf it is on (PS2). This project proposes a web-based system in which staff record stock-in, stock-out and adjustments by scanning the part's barcode/QR code and the shelf's QR label with a phone or laptop camera. The system shows the quantity of every part per zone, rack and shelf, raises low-stock alerts, keeps an audit trail, and provides a read-only AI stock assistant that answers typed or spoken questions (for example, "How many Myvi front brake pads are left, and where?"). The language model only interprets the question; quantities and locations always come from the database.

## Repository contents

| Folder | Contents |
|---|---|
| `01_Report/` | Not included in this public repository; the report is submitted to the university separately |
| `02_Presentation/` | Presentation slides (to be added) |
| `03_Prototype/` | Clickable HTML prototype (open `StockLine_Prototype.html` in a browser; it uses sample data only) |
| `04_Diagrams/` | draw.io source files (use case, class, ERD, DFD, activity, sequence diagrams and wireframes) and exported figures named by report figure number |
| `05_References/` | Reference checklist with links to every cited source |

## Planned technology (Project II)

Rust (Axum, SQLx) · MySQL · Askama templates with Bootstrap · html5-qrcode for browser camera scanning · Web Speech API for voice input and output · a hosted LLM API for question interpretation · Argon2 password hashing · HTTPS.

## Status

Project I covers the problem analysis, literature review, requirements, system design and a clickable prototype. The working system (source code), testing with 5–10 participants and demo videos will be added to this repository in Project II.
