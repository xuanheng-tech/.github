# Xuanheng Technology

Open-source software for local coding-agent workflows and quantitative research infrastructure.

## Open-source tools

### [Snapshot Runner](https://github.com/xuanheng-tech/snapshot-runner)

Deterministic, read-only Git evidence for coding agents and automation. Collects repository state, changes, branch history, or an existing test log into local artifacts. It does not modify the inspected repository, run tests, call a model, commit, or push.

Current stable release: **2.1.0**.

```bash
python3.12 -m pip install 'snapshot-runner==2.1.0'
snapshot-runner --help
```

### [Context Loader](https://github.com/xuanheng-tech/context-loader)

Deterministic, bounded local Git context for one working tree, as Markdown or JSON. Reads repository state and a fixed set of root files without fetching, executing repository code, network access, or writes to the target repository.

Current stable release: **1.1.0**.

```bash
pip install 'context-loader==1.1.0'
project-context --repo /path/to/repo
```

## Connect

- Website: [https://www.xuanhengtech.cn](https://www.xuanhengtech.cn)
- X: [@xuanhengtech](https://x.com/xuanhengtech)
- Email: contact@xuanhengtech.cn
