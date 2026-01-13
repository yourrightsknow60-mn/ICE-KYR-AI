# how-to-create-the-gems.md

## How to Create the ICE Encounters Safety Gem (Google Gemini)

This guide walks through setting up the ICE Encounters Safety system as a **Gemini Gem**, using the files in this repository.

---

## Prerequisites

- Access to **Google Gemini** with Gem creation enabled
- This repository cloned or downloaded
- Jurisdiction-specific hotlines or resources ready (optional but recommended)

---

## Step 1: Create a New Gem

1. Open Google Gemini
2. Select **Create a Gem**
3. Name the Gem (e.g., *ICE Encounters Safety – MN*)
4. Set visibility according to your organization’s needs

---

## Step 2: Add System Instructions

1. Open **System Instructions**
2. Paste the full contents of:
   - `ICE-encounters-gem-prompt.md`
3. Save

This file defines:
- What the Gem can and cannot do
- Safety constraints
- Interaction modes
- Tone and escalation limits

Do **not** modify this file casually. Changes should be intentional and reviewed.

---

## Step 3: Upload the Knowledge Base

1. Navigate to **Knowledge Base**
2. Upload **all files** inside:
   - `/knowledge-base/`
3. Confirm files are indexed and readable

These files ground the Gem’s responses and prevent hallucination.

---

## Step 4: (Optional) Customize for Your Region

You may safely customize:
- Local rapid-response hotlines
- State-specific rights or procedures
- Language availability

Avoid adding speculative or tactical content.

---

## Step 5: Test Safely

Run test prompts such as:
- “ICE is at my door right now”
- “What are my rights at work?”
- “What kind of warrant is this?”

Confirm the Gem:
- Prioritizes safety
- Avoids legal advice
- Does not escalate or speculate
- Clearly distinguishes options vs instructions

---

## Step 6: Deploy or Share

You may:
- Use internally
- Share with partner organizations
- Fork and rebrand for local use

Do not present the Gem as legal counsel.

---

## Maintenance Notes

- Review knowledge base materials regularly
- Update hotlines and policies as needed
- Keep a changelog for transparency

---

## Guiding Principle

This system is designed to **reduce harm under uncertainty**.  
When in doubt, prioritize clarity, restraint, and human support.
