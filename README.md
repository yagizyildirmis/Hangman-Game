# Adam Asmaca Oyunu (Hangman Game)

Bu proje, Java Swing kullanılarak geliştirilmiş bir masaüstü "Adam Asmaca" oyunudur. Kullanıcılar, dosyadan rastgele seçilen kelimeleri harf veya kelime tahmini yaparak bulmaya çalışır.

## Proje Özellikleri
- **Kullanıcı Doğrulama:** Oyun başlangıcında şifre korumalı giriş sistemi.
- **Dinamik Veri Yönetimi:** Kelimeler, skorlar ve log kayıtları `C:\P2Oyun` dizinindeki metin dosyalarında tutulur.
- **Otomatik Kurulum:** Eğer gerekli klasörler (TXTDosyalar, Resimler) yoksa, program bunları otomatik olarak oluşturur.
- **Loglama Sistemi:** Yapılan her işlem tarih ve saat damgasıyla `log.txt` dosyasına kaydedilir.
- **Eski Skorlar:** Oynanan oyunların süreleri ve sonuçları skor tablosunda tutulur.

## Kurulum ve Gereksinimler
Programın sorunsuz çalışması için C diskinin kök dizininde şu yapının olduğundan emin olun:
- `C:\P2Oyun\TXTDosyalar` (sifre.txt, log.txt, oyunlar.txt, kelimeler.txt dosyaları buradadır)
- `C:\P2Oyun\Resimler` (1.jpg'den 11.jpg'ye kadar resim dosyaları buradadır)

*Not: Eğer dosyalar eksikse program otomatik oluşturacaktır, ancak görselleri manuel olarak Resimler klasörüne eklemeniz gerekmektedir.*

## Kullanım
1. Uygulamayı çalıştırın.
2. İlk girişte bir şifre oluşturun.
3. Oyun sekmesinden harf veya kelime tahminlerinizi yapın.
4. "Eski Skorlar" sekmesinden geçmiş oyun kayıtlarını görüntüleyebilirsiniz.
5. Verileri temizlemek için şifrenizi girerek ilgili temizleme butonlarını kullanabilirsiniz.

## Teknik Detaylar
- **Dil:** Java
- **Arayüz:** Swing (JFrame)
- **Dosya Sistemi:** java.io, java.nio.file
