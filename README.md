# QuantumCore (quantumcore.cloud)

> Tokenized, programmable financial core and intent-routing layer with smart contract security guardrails for autonomous AI agents.

## 1. Network & Deployments (Ethereum Sepolia)

| Contract | Address | Verification |
| :--- | :--- | :--- |
| QuantumVault | 0x82A11A9e65B927B0652A84b331EAeDBa6D11d6f0 | https://sepolia.etherscan.io/address/0x82A11A9e65B927B0652A84b331EAeDBa6D11d6f0 |
| TestUSD (qUSD) | 0x2E7cf43296Fe3a157c9C28c011629bd0BA0A307E | https://sepolia.etherscan.io/address/0x2E7cf43296Fe3a157c9C28c011629bd0BA0A307E |

### On-Chain Guardrail Policy
* Single Transaction Cap: $5.00
* Rolling Hourly Limit: $20.00
* Settlement Token: 6 decimal USD stablecoin

## 2. Quickstart

pip install -e .
python cli.py limits
python crew_runner.py
