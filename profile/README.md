<div align="center">
  <img src="assets/xin-banner.svg" alt="Xinproxy — your edge, reimagined" width="100%">

  <br><br>

  [Website](https://xinproxy.com) · [Get started](https://xinproxy.com/docs/getting-started) · [Documentation](https://xinproxy.com/docs) · [Downloads](https://xinproxy.com/releases)
</div>

## Meet xin

**xin** is a reverse proxy and web server with a memory-safe Rust core. It reads a tested subset of nginx configuration, so familiar routing and operational commands carry over. Its built-in MCP gateway brings tool routing, policy, and logging to the same edge.

```nginx
server {
    listen 80;
    server_name example.com;

    location / {
        proxy_pass http://127.0.0.1:3000;
    }
}
```

Start with the [quickstart](https://xinproxy.com/docs/getting-started), or [compare configuration support](https://xinproxy.com/docs/configuration) before moving an existing site. xin is in preview; test your configuration with `xin -t`.

## Explore

| | |
| --- | --- |
| **Install xin** | [Packages and downloads](https://xinproxy.com/releases) for Linux, macOS, FreeBSD, and Windows |
| **Build with xin** | [Configuration reference](https://xinproxy.com/docs/configuration) and [MCP gateway guide](https://xinproxy.com/docs/mcp) |
| **Certbot integration** | [Our Certbot fork](https://github.com/xinproxy/certbot), with Xin support alongside upstream Certbot |
| **Homebrew** | [xinproxy/homebrew-tap](https://github.com/xinproxy/homebrew-tap) |

Questions about xin or commercial use? [Get in touch](https://xinproxy.com/#contact).
