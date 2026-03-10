# 💍 Wedding Invitation — Youngyeon & Dongjin

> Mobile-first wedding invitation web page  
> **June 27, 2026 · Irum Wedding Convention, Seoul**

---

## 📁 Project Structure

```
wedding-card/
├── index.html              # Single-page wedding invitation
├── fonts/
│   ├── GreatVibes-Regular.ttf       # Script font (hero, footer)
│   ├── KyoboHandwriting2020pdy.ttf  # Serif font (section headings)
│   └── JejuMyeongjo.ttf             # Body font (Korean body text)
├── images/
│   ├── ogtag_images.jpg    # Hero background
│   ├── og_image.jpg        # Open Graph / KakaoTalk share thumbnail
│   ├── footer_images.jpg   # Footer background
│   └── gallery_01.webp     # Gallery images (01 – 18)
│       ...
│       gallery_18.webp
└── README.md
```

---

## ✨ Features

- **Hero section** — layered depth effect with Ken Burns animation
- **Countdown timer** — live D-day counter to the wedding date
- **Calendar** — June 2026 with animated highlight on the 27th
- **Interactive map** — deep-links to Naver Maps & Kakao Maps
- **Gallery** — 3×3 grid with lightbox, expand/collapse toggle
- **Gift accounts** — accordion UI with clipboard copy & KakaoPay deep-link
- **Contact** — one-tap call for both families
- **KakaoTalk share** — Kakao SDK integration with OG metadata
- **Sticky header** — scroll-aware with progress bar

---

## 🛠 Tech Stack

| | |
|---|---|
| **Language** | HTML5 / CSS3 / Vanilla JS (no frameworks) |
| **Fonts** | Self-hosted (Great Vibes, Kyobo Handwriting, Jeju Myeongjo) |
| **Maps** | Naver Maps Embed API |
| **Share** | Kakao JavaScript SDK v2 |
| **Hosting** | GitHub Pages |

---

## 🚀 Getting Started

No build step required. Open directly in a browser:

```bash
# Clone
git clone https://github.com/yoyonie/wedding-card.git
cd wedding-card

# Serve locally (Python)
python3 -m http.server 8080
# → http://localhost:8080
```

> ⚠️ Kakao SDK and Naver Maps require the page to be served over HTTP/HTTPS, not via `file://`.

---

## 🗺 Venue

**이룸웨딩컨벤션 5F**  
서울 마포구 마포대로 78 (공덕역 1번 출구, 도보 3분)  
Coordinates: `37.5419163, 126.9498023`

---

## 📄 License

Personal project — all rights reserved.  
© 2026 Lim Dongjin & Park Youngyeon
