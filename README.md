# YBÜ Antibiyotik Karar ve Doz Destek Sistemi v2.1

## v2.1 düzeltmesi

- Kolistin, sefoperazon–sulbaktam, IV fosfomisin, tigesiklin ve ekinokandinler için somut yükleme/idame dozları eklendi.
- CrCl, HD ve CRRT'ye göre ilgili doz dalları eklendi.
- Kolistin CBA–milyon IU dönüşümü ve birim güvenliği uyarısı eklendi.
- Tigesiklin için Child–Pugh C ayarı, yüksek doz seçeneği ve HAP/VAP–bakteriyemi–üriner odak uyarıları eklendi.

## v2.0 yenilikleri

- Hastanede yatarken gelişen sepsis için son 7 gündeki antibiyotik tedavisine göre dört dallı karar algoritması eklendi.
- Ünite florasının belirleyici olduğu uyarısı görünür hale getirildi.
- Cerrahpaşa Candida skoru girişi ve skor ≥4 olduğunda ekinokandin düşünülmesi desteği eklendi.
- Kolistin, Sulperazon, Fosfomisin, Tigesiklin ve Ekinokandin seçeneklerinin doz modülüne aktarımı eklendi.

GitHub Pages üzerinde çalışan, iPhone/iPad ana ekranına kurulabilen çevrimdışı PWA paketidir.

## GitHub'a yükleme

1. GitHub'da yeni bir repository oluşturun.
2. Bu ZIP dosyasını açın ve **klasörün içindeki dosyaların tamamını** repository'nin ana dizinine yükleyin.
3. Repository'de **Settings → Pages** bölümünü açın.
4. **Build and deployment** altında `Deploy from a branch` seçin.
5. Branch olarak `main`, klasör olarak `/(root)` seçip **Save** düğmesine basın.
6. GitHub'ın verdiği Pages adresini Safari'de açın.

## iPhone/iPad ana ekranına ekleme

1. GitHub Pages adresini **Safari** ile açın.
2. Paylaş düğmesine dokunun.
3. **Ana Ekrana Ekle** seçeneğini seçin.
4. Uygulama bundan sonra ana ekrandaki ikonla açılır ve ilk ziyaretten sonra çevrimdışı da kullanılabilir.

## Güncelleme notu

Dosyaları GitHub'da değiştirdikten sonra Safari eski sürümü gösterirse uygulamayı tamamen kapatıp yeniden açın. Gerekirse ana ekran ikonunu kaldırıp Pages adresinden tekrar ekleyin.

## Klinik güvenlik

Bu araç reçete veya order oluşturmaz; klinik kararın yerine geçmez. Lokal direnç verileri, güncel ürün bilgileri, böbrek fonksiyonunun seyri, TDM olanakları ve hasta özellikleri sorumlu hekim tarafından ayrıca değerlendirilmelidir.

## Başlıca doz kaynakları

- Coly-Mycin M (kolistimetat sodyum) FDA ürün bilgisi: https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/050108s041lbl.pdf
- Uluslararası polimiksin konsensüsü: https://pmc.ncbi.nlm.nih.gov/articles/PMC7437259/
- Sulperazon Pfizer ürün bilgisi: https://labeling.pfizer.com/ShowLabeling.aspx?id=14308
- IVOZFO IV fosfomisin ürün monografı: https://pdf.hres.ca/dpd_pm/00067823.PDF
- Tygacil FDA ürün bilgisi: https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/021821s056lbl.pdf
- Anidulafungin FDA ürün bilgisi: https://www.accessdata.fda.gov/drugsatfda_docs/label/2020/021632s030lbl.pdf
- Kaspofungin FDA ürün bilgisi: https://www.accessdata.fda.gov/drugsatfda_docs/label/2021/021227Orig1s040lbl.pdf
