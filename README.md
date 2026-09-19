# Kevin Marchwiak

[AI Coordinator: screenshots and technical case study](https://github.com/xkevinemx/xkevinemx/blob/main/AI-Coordinator-Case-Study.md)

I build voice AI around the work a business needs to get done after a conversation.

Founder at **Anahera**, based in **Las Palmas de Gran Canaria, Spain**. My work combines ElevenLabs agent design, API integrations and product development with recruitment entrepreneurship, team leadership and marketing.

[Anahera and product demos](https://anahera.es) · [AI Recruiter](https://recruiter.anahera.pl) · [LinkedIn](https://www.linkedin.com/in/xkevinemx/) · [Email](mailto:kevin@anahera.es)

## Selected work

### AI Recruiter: voice intake connected to recruitment operations

A candidate speaks with an ElevenLabs agent, confirms their details and submits an application through a protected webhook. The backend stores structured information in Cloudflare D1 and exposes it through a private recruiter dashboard.

- **My contribution:** product requirements, conversation design, agent configuration, backend integrations and workflow acceptance checks.
- **Integration:** ElevenLabs SDK and tools, Cloudflare Workers/Pages and D1, Meta WhatsApp Cloud API, consent-based follow-ups and inbound message webhooks.
- **Language coverage:** seven agent languages: Polish, Dutch, English, German, Spanish, Romanian and Ukrainian.
- **Boundary:** the system collects information; human recruiters make hiring decisions. It does not score or reject candidates.

[Explore AI Recruiter](https://recruiter.anahera.pl)

### AI Receptionist: booking tools with conversation context

A voice receptionist demonstrates booking, rescheduling, cancellation and location requests. Each visitor's public demo actions belong to an isolated workspace. Fictional business bookings remain separate from real sales meetings.

- **My contribution:** session-specific context, agent tools, booking flows and consent-based WhatsApp integration.
- **A concrete fix:** a short acknowledgement such as “Vale” after a confirmed sales-demo booking previously risked restarting the sales conversation. The updated flow checks existing booking context first, while preserving the path for genuine follow-up questions.
- **Validation:** the documented change passed 16 focused regression tests and 251 tests in the wider sales automation suite. These are technical checks, not claims of customer conversion gains.

[Product overview and demos](https://anahera.es)

### Anahera Voice / AI Coordinator: structured worker-support workflows

Demonstrates how calls about absence, transport, housing and shifts can become structured cases in an operational dashboard.

My work covers the scenarios, ElevenLabs agent configuration, backend tools and the handoff from conversation to case. Public demonstrations use fictional worker data and do not submit reports to a visitor's employer.

### Anahera Med / AI Patient: appointment workflow demonstration

A custom ElevenLabs SDK interface connects voice requests to a test calendar. The demo supports availability checks, bookings, changes and cancellations. It uses fictional patient data and does not provide medical advice.

## Private RAG and project knowledge

I built a shared knowledge service for approved project documentation and technical updates. It gives development work a traceable reference across projects.


definition of approved sources → versioned ingestion → OpenAI embeddings
→ PostgreSQL + pgvector → semantic and keyword retrieval
→ scoped REST / MCP interfaces and the Atlas dashboard

- Hybrid retrieval combines vector similarity and keyword search, with access filters applied before retrieval.
- Source references and document versions are preserved; new updates do not erase the history.
- GitHub Actions synchronizes approved project updates.
- ChatGPT has a verified document-reading path; this is distinct from semantic retrieval through the knowledge service.
- The system does not automatically ingest all conversations, repositories or customer data.

The service and business application repositories remain private. This profile presents public summaries rather than production source code or customer records.

## How I work

I spend hours in sustained development sessions with **Codex**, moving between requirements, implementation, debugging and testing. I direct the work, review the result and own the product and integration decisions. I use AI tools openly and distinguish implemented features, controlled demos and measured outcomes.

My stack includes **ElevenLabs, JavaScript, TypeScript, Node.js, React, Next.js, Twilio, Meta WhatsApp Cloud API, Cloudflare Workers/Pages/D1, Render, OpenAI embeddings, PostgreSQL, pgvector, MCP and GitHub Actions**.

## Business and leadership

- Founded Anahera Recruitment and built pracaholandia.info.
- Former co-founder of Raissa Intermediar; left around 2023 after working on technology implementation and process design.
- Through OnlineRecruiter, taught and mentored people to launch and run recruitment agencies, and managed the project's marketing and social media.
- Attended Funnel Hacking Live and multiple 10X Growth Conferences; maintain an international business network.

**Languages:** Polish native · English C2 · Dutch B2 · Spanish A2-B1 (self-assessed) · German A2.

Interested in voice AI solutions work that combines customer understanding with practical implementation. Based in Spain, available immediately and able to travel regularly to Madrid and customer sites.
