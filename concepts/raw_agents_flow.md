Task from client
↓
Context gatherer
- query Git Nexus MCP
- inspect relevant files
- map impacted flows

↓
Implementation planner
- produce checklist
- identify test scenarios
- identify risky edge cases

↓
Coder
- implement code
- no tests yet, or tests in same pass depending on task size

↓
Test writer
- unit tests
- integration tests
- e2e tests
- regression tests for reported bug

↓
Automated test runner
- PHPUnit / Pest
- Jest / Vitest
- Playwright / Cypress
- static analysis / lint / typecheck

↓
Browser verification agent
- use Chrome DevTools MCP
- manually navigate UI
- check flows
- inspect console/network/storage
- record reproduction steps

↓
Failure analyst
- summarize failing scenario
- identify suspected cause
- send back to coder

↓
Repeat until pass or blocked

↓
Final report
- changed files
- tests added
- commands run
- scenarios manually checked
- remaining risks
