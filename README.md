# 📅 Calendar AI Agent (n8n)

Calendar AI Agent is an **AI-powered workflow built with n8n** that enables users to create Google Calendar events using **natural language commands** via chat.

---

## ✨ Features

- Chat-based trigger using **n8n Chat Trigger**
- Understands natural language inputs  
  (e.g. _"Create a meeting tomorrow at 2 PM"_)
- Automatically extracts:
  - Event title
  - Date & time
  - Duration (defaults to 1 hour if not specified)
- Creates events directly in **Google Calendar**
- Confirms the booking via chat response

---

## 🛠️ Tech Stack

- **n8n (AI Agent)**
- **OpenAI Chat Model**
- **Google Calendar API**

---

## ⚙️ Workflow Overview

1. User sends a message via Chat Trigger
2. AI Agent parses intent and event details
3. Google Calendar node creates the event
4. Agent confirms the result back to the user

---

## 📸 Documentation

Screenshots of the workflow and execution results are available at:

![SS](/img/ss.png)

---

## 🚀 Example Commands

- `Create a meeting tomorrow at 2 PM`
- `Block my calendar for a meeting at 3 PM today`
- `Schedule a team sync next Monday at 10 AM`

---

## 🔐 Requirements

- Google Calendar credentials connected in n8n
- OpenAI API key configured in n8n
- n8n AI Agent feature enabled

---

## 📄 License

This project is for educational and experimental purposes.
