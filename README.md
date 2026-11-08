# YAJU-proxy

A lightweight proxy shell with a safe allowlist, search, tabs, bookmarks, private mode, and node health checks.

## Run

```bash
cargo run -p gateway -- --port 8080
cargo run -p proxy-node -- --port 9001
cargo run -p proxy-node -- --port 9002
cargo run -p proxy-node -- --port 9003
```

Set `ALLOWED_HOSTS` to restrict domains, for example:

```bash
ALLOWED_HOSTS="example.com,www.example.com,localhost,github.com,duckduckgo.com" cargo run -p gateway -- --port 8080
```
