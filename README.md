# Forum Pro – CSS & JS (GitHub / GitLab Pages)

- `css/style.min.css` : tüm tema CSS'i (tek dosya)
- `js/app.min.js`     : dil paketi (TR/EN) + tüm JavaScript (tek dosya)

## GitHub Pages
1. Yeni depo oluşturun, bu klasörün içeriğini yükleyin (`.nojekyll` dahil).
2. Settings → Pages → Branch: `main` / `(root)` → Save.
3. Adresler: `https://KULLANICI.github.io/REPO/css/style.min.css` ve `.../js/app.min.js`

## GitLab Pages
Depoya yükleyin; `.gitlab-ci.yml` otomatik yayınlar.
Adresler: `https://KULLANICI.gitlab.io/REPO/css/style.min.css` ve `.../js/app.min.js`

## Temada adresi düzeltme
`Mifrm_SEO_temiz.xml` içindeki `https://KULLANICI.github.io/REPO` kısmını kendi adresinizle değiştirin (2 yer).
Dosyaları güncellediğinizde önbelleği yenilemek için `?v=1` değerini `?v=2` yapın.
Not: Arama botları dosyalara erişebilmeli; Pages adresini robots.txt ile engellemeyin.
