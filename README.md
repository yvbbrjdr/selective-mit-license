# Selective MIT License

This repository contains templates for a Selective MIT License: an MIT-style software license that grants the usual MIT permissions to most recipients while excluding named people or organizations.

The goal is to keep the familiar structure and permissive defaults of the MIT License, while making it explicit that specific parties listed in Appendix A do not receive permission to use, copy, modify, distribute, sublicense, or sell the software.

## Files

- [`SMIT.txt`](SMIT.txt): Base template with placeholders for excluded natural persons and organizations.
- [`SMIT-oai.txt`](SMIT-oai.txt): Template excluding OpenAI Group PBC.
- [`SMIT-ant.txt`](SMIT-ant.txt): Template excluding Anthropic, PBC.
- [`SMIT-oai-ant.txt`](SMIT-oai-ant.txt): Template excluding both OpenAI Group PBC and Anthropic, PBC.

## How To Use

1. Choose the template that matches the exclusions you want.
2. Replace `[year]` and `[fullname]` with your copyright year and copyright holder name.
3. Edit Appendix A to list the excluded natural persons or organizations.
4. Include the completed license text in your project, usually as `LICENSE` or `LICENSE.txt`.

If you need to exclude additional parties, start from [`SMIT.txt`](SMIT.txt) and add them under the appropriate Appendix A section.

## Repository License

This repository and its license templates are published under CC0 1.0 Universal, as specified in [`LICENSE`](LICENSE).

## Important Note

These templates are provided for convenience and discussion. They have not been validated by a court, may not satisfy open source definitions that require non-discrimination, and may have consequences for package registries, communities, or downstream users that expect OSI-approved licenses.

This is not legal advice. If enforceability or compliance matters for your project, consult a qualified attorney before relying on this license.
