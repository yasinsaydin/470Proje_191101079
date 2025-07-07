# Spam Detection Project

Bu projede iki farklı veri seti üzerinde spam tespiti için klasik makine öğrenmesi ve derin öğrenme yöntemleri uygulanmıştır.

- `data/` klasöründe kullanılan veri setleri:
  - spam.csv (SMS)
  - spam_ham_dataset.csv (Email)

- `models/` klasöründe eğitilmiş modeller:
  - sms_RandomForest.pkl
  - sms_AdaBoost.pkl
  - sms_MLP.pkl
  - sms_KNN.pkl
  - sms_LinearSVC.pkl
  - sms_ensemble.pkl
  - lstm_email.h5

- `spam_detection.ipynb`: Tüm veri analizi, model eğitimi ve değerlendirme kodları ile çıktıları içerir.
- `test_model.ipynb`: Kaydedilmiş modellerle test yapmayı gösteren örnek notebook.

## Kullanım
1. Notebook’u açın ve çıktıları gözlemleyin. (Tüm çıktı hücreleri bırakılmıştır.)
2. Yeniden çalıştırmak isterseniz:
   - Gerekli kütüphaneleri yükleyin
   - Gerekirse veri setlerini güncelleyin
   - Notebook’un tüm hücrelerini sırasıyla çalıştırın

## Notlar
- Modeller notebook içerisinde eğitildikten sonra `models/` klasörüne kaydedilmektedir.
- Tüm kod ve analiz adımları `spam_detection.ipynb` dosyasındadır.
- Notebook’ta yer alan çıktılar, eğitimin her adımında elde edilen sonuçları içermektedir.
- Kod ve veri tamamen proje sahibine aittir, dış kaynak kodları için açıklama satırlarında referans verilmiştir.

