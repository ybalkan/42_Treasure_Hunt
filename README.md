# 🧭 Hazine Avı (CTF)

<img width="1024" height="1536" alt="IMG_6370" src="https://github.com/user-attachments/assets/baea2253-8501-4aef-a348-26d1114c5192" />

### 42 Kocaeli – Sistem Programlama & Tree Topology Challenge

> 👨‍💻 **Geliştirici:** ybalkan  
> 🎓 **Okul:** 42 Kocaeli  
> ⚙️ **Tür:** Capture The Flag (CTF) / Sistem Programlama Bulmacası  

---

## 🧩 Proje Hakkında

**Hazine Avı (CTF)**, terminal tabanlı interaktif bir bulmacadır ve şu konseptleri birleştirir:

- 🌳 Ağaç (tree) veri yapısı mantığı  
- 💻 C ile sistem programlama  
- 🧠 Bellek yönetimi ve runtime çözümleme  
- 🔐 Reverse engineering (tersine mühendislik)  

Oyuncu, gizli bir sistem içinde ilerleyerek şifreli verileri çözer ve finalde gizli anahtarı bulur.

---

## ⚠️ Güvenlik / Tasarım Notu

Bu proje bilinçli olarak **obfuscate (karartılmış)** şekilde tasarlanmıştır:

- `data.h` dosyası XOR ile şifrelenmiştir  
- Sorular sadece **çalışma zamanında (runtime)** açılır  
- Statik kod incelemesi yeterli değildir  
- Amaç kodu okumak değil, sistemi anlamaktır  

---

## 🚀 Kurulum

```bash
git clone https://github.com/KULLANICI_ADIN/REPONUN_ADI.git
cd REPONUN_ADI
make
