# SmartHire-AI
AI-powered recruitment automation workflow built with n8n and Groq AI.

## Features

- Resume Analysis using Groq AI
- Candidate Scoring
- Skill Extraction
- Recommendation Generation
- Interview Question Generation
- Airtable Storage
- Google Sheets Logging
- Gmail Notifications
- Google Calendar Interview Scheduling
- Slack Notifications

## Tech Stack

- n8n
- Groq AI
- Airtable
- Google Sheets
- Gmail
- Google Calendar
- Slack

## Workflow

<img width="738" height="325" alt="image" src="https://github.com/user-attachments/assets/7648c6f5-6595-4d69-b1f2-036b04e65d45" />

<img width="736" height="400" alt="image" src="https://github.com/user-attachments/assets/5ca529ea-a881-43e4-8d03-d918deff206b" />



## Architecture

Webhook

↓

Groq AI

↓

Parse JSON

↓

IF Score

↓

Airtable

↓

Google Sheets

↓

Gmail

↓

Calendar

↓

Slack

## Future Improvements

- OCR Resume Parsing
- PDF Resume Upload
- Multiple Job Roles
- ATS Integration
- HR Dashboard
