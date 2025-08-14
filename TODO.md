+# Plano de Tarefas
+
+## Fase 0 – Preparação
+
+- [x] Criar estrutura do monorepo (`/client`, `/api`, `/worker`, `/supabase`).
+- [x] Configurar lint, prettier e testes com CI básico.
+- [ ] Configurar ambiente Docker Compose (api, worker, nginx, Postgres/Supabase).
+- [ ] Definir schema inicial do banco com RLS e migrations.
+- [x] Documentar fluxo de contribuição e padrões de código.
+
+## Release 1 – MVP do Chat & RAG Básico
+
+- [ ] Implementar Auth e tabelas `profiles`, `projects`, `conversations`, `messages`.
+- [ ] Criar endpoint `/api/chat` com streaming e registro de custo/logs.
+- [ ] Implementar ingestão e busca híbrida (BM25 + vetor).
+- [ ] Integrar leitura de Notion e Google Drive/Docs com consentimento.
+- [ ] Criar PWA básico (manifest e service worker simples).
+- [ ] Implementar RLS e orçamento mínimo por usuário.
+
+## Release 2 – Modo MAX, Estúdio de Agentes & Memória
+
+- [ ] Implementar fluxo `planner → executor → critic → commit`.
+- [ ] Construir Estúdio de Agentes (CRUD de manifests).
+- [ ] Adicionar ferramentas de escrita `notion.write` e `gdocs.write`.
+- [ ] Implementar memória explicável com TTL por tipo.
+- [ ] Adicionar logs básicos de toolcalls e custo.
+
+## Release 3 – Hub de Ferramentas, Governança & Observabilidade
+
+- [ ] Criar Tool Registry e endpoints de invocação.
+- [ ] Implementar bridge MCP para ferramentas externas.
+- [ ] Construir Consent Manager e cofre de segredos.
+- [ ] Expor métricas de custo, latência e taxa de erro.
+- [ ] Implementar budget avançado e DLP.
+
+## Release 4 – PWA Avançado, Replays & Endurecimento
+
+- [ ] Implementar fila offline e push notifications.
+- [ ] Adicionar replay e depuração de conversas/toolcalls.
+- [ ] Realizar testes de segurança (RLS, DLP) e correções.
+- [ ] Polir UI com templates e onboarding.
