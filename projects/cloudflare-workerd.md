# cloudflare/workerd

**GitHub**: https://github.com/cloudflare/workerd

**Language**: C++

## Description

The JavaScript / Wasm runtime that powers Cloudflare Workers. (Pronounced: "worker-dee")

**You might use it:**
- As an application server, to self-host applications designed for Cloudflare Workers
- As a development tool, to develop and test such code locally
- As a programmable HTTP proxy (forward or reverse), to efficiently intercept, modify, and route network requests

**Key Principles:**
- Server-first: Designed for servers, not CLIs nor GUIs
- Standard-based: Built-in APIs are based on web platform standards (fetch())
- Nanoservices: Split your application into independently-deployable components
- Capability bindings: Uses capabilities instead of global namespaces (immune to SSRF attacks)
- Always backwards compatible

## AI Summary

workerd is an open-source JavaScript/Wasm server runtime based on the same code that powers Cloudflare Workers. It allows developers to self-host Workers-compatible applications, test locally, or use as a programmable HTTP proxy. The runtime follows server-first principles with standard-based APIs and unique nanoservices architecture.

## Trending History

- **2026-03-18**: +31 stars today

---
*Last updated: 2026-03-18*
