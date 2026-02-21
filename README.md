# agent-identity-trust-fabric

Identity and trust primitives for agent authentication, key exchange, and policy-aware access.

## Scope

Agent IDs, trust chains, short-lived credentials, and cryptographic service identity.

## Capabilities

- Agent IDs, trust chains, short-lived credentials, and cryptographic service identity.
- PKI integration with cert rotation and trust attestation.
- Signed service-to-service auth with role and policy checks.
- Zero-trust compatibility, auditability, and deterministic auth decisions.

## Repository Layout

- `src/main.py` entrypoint and lightweight service bootstrap
- `src/project_profile.py` canonical project metadata
- `src/service_contract.py` baseline domain contract shape
- `tests/` smoke and contract tests
- `docs/` architecture and roadmap

## Quick Start

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
pytest -q
python -m src.main
```
