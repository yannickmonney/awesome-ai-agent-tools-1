# Awesome AI Agent Tools

[![links](https://github.com/nosmile99/awesome-ai-agent-tools/actions/workflows/links.yml/badge.svg)](https://github.com/nosmile99/awesome-ai-agent-tools/actions/workflows/links.yml)

A curated list of tools for **AI agents that do real work** — frameworks, dev harnesses, inspectors, and evaluators. Not a list of chatbots: every entry here is something an agent (or its human) can pick up and use.

PRs welcome — see [CONTRIBUTING](CONTRIBUTING.md).

## Agent dev tooling

Tools for building, inspecting, and iterating on what agents produce.

- [rundiff](https://github.com/nosmile99/rundiff) — Diff two run directories: images get a before/after slider, text gets unified diffs. For `run-001` vs `run-002` iteration loops.
- [nbt-inspect](https://github.com/nosmile99/nbt-inspect) — Inspect Minecraft `.nbt` structure files from the CLI: dimensions, block palette counts, entities.
- [mcbuilder](https://github.com/lzif/mcbuilder) — Python tooling for AI agents that build Minecraft structures: builder DSL, block-registry validation, preview renders, `.nbt` export. Agent-first API design (error provenance, determinism).
- [Shulkr](https://www.shulkr.com) — In-browser 3D viewer for `.nbt` / `.schem` / `.litematic` / `.mcstructure` files. Fully client-side, nothing uploaded.
- [ComputeFirst](https://github.com/321zz321/computefirst-skill) — Agent skill and MCP connection kit for deterministic calculations, identifier validation and data transforms through a free hosted service; no API key required.

## Frameworks

- [markupless](https://github.com/lzif/markupless) — TypeScript UI framework with implicit reactivity and no build step. Interesting to agents for its "magic" argument-inference API design.

## Libraries agents should know

- [nbtlib](https://github.com/vberlier/nbtlib) — Python library to read and edit NBT data. The foundation under most Minecraft-adjacent agent tooling.

## Contributing

Found a tool that belongs here? Open a PR — one line, one link, one honest sentence about what it does. See [CONTRIBUTING](CONTRIBUTING.md).

## License

This list is MIT-licensed — see [LICENSE](LICENSE). Linked projects keep their own licenses.
