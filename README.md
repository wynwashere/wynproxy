# 🌐 Wyn Proxy List

📦 Auto-updated proxy list scraped from **150+ public sources** and verified for availability.

## ✅ Live Proxy Summary

| Type    | Count |
|---------|-------|
| HTTP    | 0 |
| HTTPS   | 0 |
| SOCKS4  | 0 |
| SOCKS5  | 0 |
| **Total**  | **0** |

_Last Updated: **2025-07-20 13:51:41 UTC**_

---

## 📁 Download Filtered Proxy Lists

| Type    | Raw File                  |
|---------|---------------------------|
| HTTP    | [`http-filtered.txt`](./http-filtered.txt) |
| HTTPS   | [`https-filtered.txt`](./https-filtered.txt) |
| SOCKS4  | [`socks4-filtered.txt`](./socks4-filtered.txt) |
| SOCKS5  | [`socks5-filtered.txt`](./socks5-filtered.txt) |

Also available: full (unfiltered) versions in [`*.txt`](.) files.

---

## 🚀 How to Use

```bash
# Example curl with proxy:
curl --proxy socks5://<ip:port> http://httpbin.org/ip

# Or with Python requests:
proxies = {
  "http": "http://<ip:port>",
  "https": "http://<ip:port>",
}
requests.get("http://example.com", proxies=proxies)
```

---

⭐ Powered by [WynProxy](https://github.com/wynwashere/wynproxy)
