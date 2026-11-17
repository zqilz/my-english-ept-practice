# Comprehensive EPT/TOEFL-Level Practice Test (300 Questions)

A self-contained, browser-based academic English practice test featuring 300 questions across five sections. Designed for self-paced study (~3 hours 30 minutes recommended) with automatic progress saving and `.txt` export for external LLM grading.

## Test Structure

1. **Section 1: Listening Comprehension (Questions 1–30)**
   - Part A: Short Dialogues (Q1–10)
   - Part B: Longer Conversations (Q11–20)
   - Part C: Academic Lectures (Q21–30)
   - Includes a **Blind Listening Mode** toggle to hide scripts while playing audio.
2. **Section 2: Structure — Sentence Completion (Questions 31–110)**
3. **Section 3: Written Expression — Error Identification (Questions 111–190)**
4. **Section 4: Academic Vocabulary & Discourse Coherence (Questions 191–240)**
5. **Section 5: Reading Comprehension (Questions 241–300)**
   - 6 academic passages (10 questions each) in a side-by-side split view.

## Features

- **Auto-Save Progress:** Answers, active filters, and timer state are saved automatically to browser `localStorage`.
- **Navigation & Filtering:** Switch between sections, filter by **Unanswered Only**, or jump directly to the **Next Unanswered** question.
- **Built-in Timer:** Track your study time with Start/Pause/Resume controls.
- **Export for LLM Grading:** There are intentionally **no answer keys or automated grading** on the site. Once all 300 questions are answered, an **Export Full Test & Answers (.txt)** button unlocks at the bottom of the page.

## Project Structure

```text
.
├── toefl test.html
└── listening_audio/
    ├── 01_PartA_Dialogue_01.webm
    ├── ...
    ├── 10_PartA_Dialogue_10.webm
    ├── 11_PartB_Conversation_1.webm
    ├── 12_PartB_Conversation_2.webm
    ├── 13_PartC_Lecture_1.webm
    └── 14_PartC_Lecture_2.webm