# NEMORIZZ 네모리즈

프리미엄 웨딩·기업·페스티벌 포토부스 렌탈 서비스 공식 웹사이트.

🌐 **Live**: https://nemorizz.com

## 구성

- `index.html` — 메인 랜딩 페이지 (단일 파일, 인라인 CSS)
- `nemorizz-images/` — 히어로·갤러리·매거진·키오스크 UI 이미지/영상
- `backup/` — AI 프레임 관련 개발 백업 (배포 시 robots.txt에서 크롤 제외)

## 배포

GitHub `main` 브랜치 push → Netlify 자동 배포.

```bash
git add .
git commit -m "update: <내용>"
git push origin main
```

## 설정 파일

| 파일 | 용도 |
|---|---|
| `netlify.toml` | 빌드·압축·리다이렉트 설정 |
| `_headers` | 캐시 정책 + 보안 헤더 |
| `robots.txt` | 검색엔진 크롤링 규칙 |
| `sitemap.xml` | Google/Naver 사이트맵 |

## 연락

- 전화: 010-7359-1788
- 운영시간: 매일 09:00 ~ 22:00
- 지역: 울산 (전국 출장)
