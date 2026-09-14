# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management framework. This folder contains comprehensive guidance for managing projects, from initiation through closure and continuous improvement.

## Quick Start
For a first-time overview, start with [Project Management Overview](./octoacme-project-management-overview.md).

## Documentation Index

| Document | Purpose | Use When |
|----------|---------|----------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and artifacts | You're new to OctoAcme or need a refresher on our PM framework |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Validate and authorize new work; align stakeholders and create a lightweight plan | A new project idea or feature proposal is ready to explore |
| [Project Planning](./octoacme-project-planning.md) | Turn approved initiatives into actionable plans and backlogs | You're ready to break work into shippable increments |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress toward milestones | You're actively building and need guidance on standups, workflows, and quality |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies | You need to escalate blockers or update stakeholders |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize releases and reduce risk | You're preparing to go live or deploy to production |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements | A sprint, release, or milestone is complete |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Reference for typical roles and their responsibilities | You need to understand role definitions and communication patterns |

## OctoAcme PM Principles

Our approach is built on five core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments and learn from feedback
- **Clear ownership**: Every project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Project Lifecycle

1. **Initiation**: Validate the problem statement, identify stakeholders, and define high-level timelines
2. **Planning**: Break work into shippable increments, estimate scope, and plan releases
3. **Execution**: Build, test, review, and iterate in regular cycles
4. **Release**: Deploy, verify, and announce to stakeholders
5. **Retrospective**: Capture learnings and improve our processes

## OctoAcme Project Management Process Overview

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value iteratively while maintaining clear ownership and data-informed decision-making. Projects progress through **Initiation** (validating business need and aligning stakeholders via a One-pager), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (building and testing with regular standups and demos), **Release** (deploying to production with documented rollback plans), and **Close & Retrospective** (capturing learnings and continuous improvements). Throughout each phase, the team uses a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintains small pull requests (≤400 lines) with clear issue links and acceptance criteria. This iterative, increment-based approach minimizes risk while maintaining momentum.

### Roles and Communication Cadence

OctoAcme defines clear ownership through four core personas: **Project Managers** coordinate delivery, schedules, risks, and cross-team communication; **Product Managers** define outcomes, prioritize the backlog, and measure success against data; **Developers** implement features and contribute to estimation and risk identification; and **QA/Testing** teams validate quality and acceptance criteria. Communication follows a consistent rhythm—daily standups (15 minutes, focused on progress and blockers), weekly PM/PdM alignment syncs, twice-weekly delivery team standups, and monthly stakeholder updates. This cadence ensures transparency, early blocker detection, and alignment across engineering, product, and business stakeholders.

### Quality Assurance and Risk Management

Quality is embedded throughout execution via unit tests for new logic, integration tests where applicable, and end-to-end smoke tests before release. The team runs automated CI testing and security scanning before requesting PR reviews and requires at least one approval before merging. Risk management is proactive—risks are identified during planning and ongoing execution, captured in a Risk Register with impact/likelihood assessments, and monitored at weekly syncs. Blockers follow a three-level escalation path (team triage → PM escalation to Product Lead → sponsor-level escalation), ensuring rapid response to business-impacting issues. Pre-release requirements include passing CI/security scans, staged deployment verification, and documented rollback plans, with post-deploy verifications and stakeholder announcements completing the release cycle.

### Continuous Learning and Improvement

OctoAcme institutionalizes learning through retrospectives held after each sprint, release, or milestone, where teams reflect on what went well, identify improvements, and assign 2-3 prioritized action items with clear owners and due dates. These action items are tracked in the project backlog and reviewed during weekly PM syncs to measure their impact. The organizational culture emphasizes psychological safety, encouraging feedback and iterative refinement. By converting tacit knowledge into versioned process documents and using issue templates to standardize process updates, OctoAcme scales institutional knowledge, reduces onboarding friction, and eliminates single-person dependency risk—making consistent, repeatable project execution accessible to all team members.

## Contributing to Process Docs

If you have feedback, improvements, or new content for these process documents:

1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Include a summary of your proposed change and rationale
3. Engage with the team in the issue discussion
4. Once approved, submit a PR with your updates

## Support

For questions about these processes, reach out to your Project Manager or Product Lead.
