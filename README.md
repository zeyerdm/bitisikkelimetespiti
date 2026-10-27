# 🔤 Bitişik Kelime Tespiti

> Türkçe metinlerde yanlışlıkla bitişik yazılmış kelimeleri (ör. `kararıtemyiz`, `2012numarası`) tespit etmeyi amaçlayan metin analizi projesi.
>
> *A text-analysis project for detecting accidentally merged words in Turkish text.*

![Durum](https://img.shields.io/badge/Durum-Geli%C5%9Ftirme%20a%C5%9Famas%C4%B1nda-orange)

## 📌 Proje Hakkında

Belgeler HTML veya PDF kaynaklarından düz metne dönüştürülürken kelimeler arasındaki boşluklar kaybolabilir ve iki ya da daha fazla kelime tek bir kelime gibi birleşir. Bu durum hem okunabilirliği hem de arama, sınıflandırma ve yapay zekâ eğitimi gibi sonraki işlemlerin doğruluğunu düşürür. Bu projenin amacı, böyle birleşmeleri otomatik olarak bulup raporlamaktır.

## 🎯 Hedeflenen Özellikler

- Büyük-küçük harf geçişlerinden (`kararıTemyiz`) ve sayı-harf birleşmelerinden (`2004yargıtay`) birleşik kelime yakalama
- Anormal uzunluktaki boşluksuz kelime bloklarını işaretleme
- Sık görülen birleşme kalıpları için düzenli ifade (regex) kuralları
- Klasördeki tüm `.txt` dosyalarını tarayıp sonuçları CSV olarak raporlama

## 🔗 İlgili Proje

Bu kalıpların ilk uygulaması **Yargıtay Karar Doğrulama Botu** (`yargitay-bot`) projesindeki hızlı tarama modülünde kullanılmıştır.

## 🛠️ Planlanan Teknolojiler

- Python 3 (`re`, `csv`, `pathlib`)

## 👩‍💻 Geliştirici

**Zeynep Erdem** — [github.com/zeyerdm](https://github.com/zeyerdm)
