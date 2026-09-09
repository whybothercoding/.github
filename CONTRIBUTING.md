# Contributing

This is a default `CONTRIBUTING.md`, inherited from [whybothercoding/.github](https://github.com/whybothercoding/.github) by any repo that doesn't have its own. If the repo you're looking at has its own `CONTRIBUTING.md`, follow that one instead — it takes precedence.

## Before opening a PR

- **Open an issue first** for anything beyond a small fix — a quick description of the problem or proposal saves a wasted PR if the approach needs to change.
- **One logical change per PR.** Unrelated fixes belong in separate PRs.
- **CI must pass.** Every repo here runs build/lint/test (and typecheck, where applicable) on every push and PR — a required check, not optional. Run the same commands locally before pushing if you can; check the repo's own README for the exact commands.
- **Commit style is conventional-ish**: `feat:`, `fix:`, `docs:`, `chore:`, etc. — one logical change per commit, clear message.

## Code style

Match the existing code — indentation, naming, and idiom already in the file you're editing. Don't introduce a new formatter, linter config, or dependency-management convention without discussing it in an issue first.

## Reporting a security issue

Don't open a public issue. See [SECURITY.md](SECURITY.md).

## Questions

Open an issue with the `question` label, or reach out via the contact listed in the repo's own README.
