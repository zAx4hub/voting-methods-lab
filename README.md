# Voting Methods Lab

> Voting methods lab covering IRV and Condorcet

**Author:** zAx4hub

## Problem

Voting methods lab covering IRV and Condorcet. Teams often rely on closed SaaS, brittle scripts, or untested prototypes for this niche.

## Solution

`voting-methods-lab` is an installable TypeScript/Node toolkit by **zAx4hub** with a real **search** engine, CLI, examples, and tests.

## Why different

- Distinct niche — not a thin wrapper or todo scaffold
- Deterministic core algorithms you can unit-test
- Local-first / self-host friendly defaults
- Credited only to **zAx4hub**

## Quickstart

```bash
cd voting-methods-lab
npm install
npm test
npm run demo
```

## 60-second demo

```bash
npm run demo   # or: python -m voting_methods_lab.cli demo
```

Expect a JSON report with score, findings, and metrics — copy into your README GIF or Show HN comment.

## Features

1. Core search engine tailored to the problem
2. CLI: `demo` / `run` / `inspect`
3. Structured JSON reports with metrics
4. Examples + fixtures
5. GitHub Actions CI workflow (may remain local if token lacks workflow scope)
6. Flagship polish: sharp demo path + topics-ready description

## Architecture

`src/` (or Python package) holds pure engine logic. CLI and examples sit at the edges. Tests exercise the engine directly.

## Contributing

PRs welcome — keep changes focused and add tests. Credit remains **zAx4hub**.

## Credits

Built and maintained by **zAx4hub**.

## License

MIT © 2026 zAx4hub
