# ai-agent-robustness-testing

Research and payloads for evaluating the resilience of LLM-based browser agents and human workflows against indirect prompt injection and social engineering attacks.

---

## 🎯 Project Overview
This repository documents vulnerabilities where untrusted user input (e.g., order notes, web content) can influence the behavior of an autonomous AI agent or deceive a human reviewer.

## 🧪 Targeted Vulnerabilities

### 1. Indirect Prompt Injection (AI-Targeted)
* **Instruction Hijacking:** Using delimiters like `---` to bypass system prompts.
* **Tag Mimicry:** Using `[SYSTEM]` or `[ADMIN]` headers to trick the LLM.

### 2. Social Engineering (Human-Targeted)
* **Authority Mimicry:** Faking internal approval codes or supervisor notes.
* **Narrative Pressure:** Using high-stakes stories (e.g., charity galas) to encourage protocol bypass.

## 🛠️ Payload Categories
| Category | Mechanism | Goal |
| :--- | :--- | :--- |
| **Dual-Layer** | Narrative + Brackets | Targets both AI logic and human empathy. |
| **System Override** | `[SYSTEM]` Tags | Mimics metadata to force tool execution. |
| **Context Break** | Delimiter sequences | Resets the agent's current operational flow. |

---

## 🛡️ Disclaimer
This project is for **educational and security research purposes only**. Never use these payloads on systems you do not have explicit permission to test.
