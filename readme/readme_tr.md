# Telegram Media Analyzer (Telegram Medya Analiz Aracı)

> 🔍 Eğitim ve araştırma amaçlı geliştirilmiş, Telegram'daki herkese açık içeriklerden meta veri çıkarmayı destekleyen hafif bir ön uç aracı

🌐 Canlı Demo: [https://twittervideodownloaderx.com/telegram_downloader_tu](https://twittervideodownloaderx.com/telegram_downloader_tu)

---

## 📋 Proje Genel Bakış

Bu proje, eğitim ve teknik araştırma amaçlarıyla geliştirilmiştir. Geliştiricilerin ve öğrencilerin, standart web önizleme arayüzlerini ve yapılandırılmış veri API'lerini kullanarak herkese açık Telegram kanalları ve gruplarından yapılandırılmış meta verileri nasıl çıkarabileceklerini anlamalarına yardımcı olmak için tasarlanmış hafif bir ön uç yardımcı programıdır.

> 🎯 Önerilen Kullanım Senaryoları:
> - Kişisel çalışma materyallerinin düzenlenmesi ve fikir toplama
> - Ön uç geliştirme pratiği ve web veri çıkarma araştırmaları
> - Multimedya meta veri yapıları hakkında öğrenme
> - Telif hakkı sahiplerinden açık izin alınmış herkese açık içeriklerin arşivlenmesi

⚠️ **Önemli Uyarı**: Bu araç yalnızca **Telegram'ın web önizleme özelliği üzerinden herkese açık erişilebilir içeriklerle** çalışır. Özel kanallar, özel gruplar, giriş gerektiren içerikler veya erişim kısıtlaması olan herhangi bir içeriğe erişim sağlamak için tasarlanmamıştır ve bu amaçla kullanılmamalıdır.

---

## ✨ Temel Özellikler

- 🔗 **Herkese Açık Bağlantı Tanıma**: Telegram herkese açık kanal/grup web önizleme URL formatlarını (`t.me/username/message_id`) otomatik olarak algılar
- 🎬 **Çoklu Kaynak Türü Desteği**: Herkese açık erişilebilir videolar, görseller, belgeler ve diğer medya dosyaları için meta veri çıkarır (içeriğin herkese açık görünürlükte ayarlanmış olması gerekir)
- 📐 **Temel Bilgi Gösterimi**: Medya türü, dosya boyutu, yükleme zaman damgası ve diğer herkese açık meta verileri görüntüler
- 📱 **Tamamen Duyarlı Tasarım**: Masaüstü, tablet ve mobil cihazlarda optimize edilmiş kullanıcı deneyimi
- ⚡ **İstemci Tarafı Öncelikli Mimari**: Temel analiz mantığı tarayıcıda çalışır, sunucu bağımlılığını azaltır ve yanıt süresini iyileştirir
- 🔐 **Gizliliğe Saygılı Tasarım**: Gönderilen URL'leri kaydetmez, analiz sonuçlarını depolamaz veya herhangi bir kişisel kullanıcı verisi ya da hesap bilgisi toplamaz

---

## 🚀 Hızlı Başlangıç Kılavuzu

1. Telegram uygulamasını veya web sitesini açın ve başvurmak istediğiniz içeriği içeren **herkese açık kanalı/grubu** bulun
2. Hedef mesaja dokunun/tıklayın → «···» menüsünü seçin → Web önizleme URL'sini almak için «Bağlantıyı Kopyala»yı seçin (örnek: `https://t.me/username/123`)
3. Bağlantıyı bu aracın giriş alanına yapıştırın ve "Analiz Et" düğmesine tıklayın
4. Sistem, herkese açık meta verileri çıkaracak ve erişilebilir kaynak bilgilerini görüntüleyecektir
5. Tercih ettiğiniz kaynağı seçin, ardından bağlantıya sağ tıklayıp "Farklı kaydet..." seçeneğini seçerek yerel olarak indirin

> 💡 Kullanım İpuçları:
> - Hedef kanal/grubun ve içeriğin "Herkese Açık" görünürlük ayarında olduğundan her zaman emin olun
> - Analiz başarısız olursa, sayfayı yenilemeyi veya ağ bağlantınızı kontrol etmeyi deneyin
> - Öğrenme amaçlı olarak, bu araçla birlikte tarayıcı Geliştirici Araçlarını (F12 → Network → Fetch/XHR) kullanmayı düşünün

---

## ⚠️ Uyumluluk ve Sorumluluk Reddi (Lütfen Dikkatlice Okuyun)

Bu proje, "teknik tarafsızlık" ve "yasal uyumluluk" ilkeleri çerçevesinde faaliyet göstermektedir. Kullanmadan önce lütfen aşağıdakileri inceleyin ve kabul edin:

### ✅ Önerilen Uygulamalar
- Yalnızca yasal erişim hakkınız olan **herkese açık erişilebilir içerikleri** analiz edin
- Çıkarılan kaynakları yalnızca **kişisel öğrenme, araştırma veya özel referans** amacıyla kullanın
- Yeniden dağıtım, türev eser oluşturma veya ticari kullanım előtt telif hakkı sahiplerinden açık yazılı izin alın
- Projelerinizde her zaman orijinal yaratıcıları belirtin ve kaynak atıfını açıkça gösterin

### ❌ Yasaklanan Eylemler
- Özel kanallar, özel gruplar veya kimlik doğrulama/erişim doğrulaması gerektiren içeriklere erişmeye veya analiz etmeye çalışmak
- Bu aracı ticari kazıma, veri toplama hizmetleri veya reklam geliri elde etmek için kullanmak
- Yüksek frekanslı otomatik istekler, bot trafiği veya Telegram hizmetlerini aksatabilecek herhangi bir etkinlik göndermek
- Filigranları, telif hakkı bildirimlerini veya gömülü meta verileri kaldırmak, değiştirmek veya gizlemek
- Bu aracı gizliliği ihlal eden, yasalara aykırı olan veya fikri mülkiyet haklarını ihlal eden içeriklere erişmek, dağıtmak veya yaymak için kullanmak

> 📜 Yasal Uyarı:
> Bu aracın kullanımı, geçerli telif hakkı yasalarına, veri koruma düzenlemelerine ve Telegram'ın [Kullanım Şartları](https://telegram.org/tos) ile [Gizlilik Politikası](https://telegram.org/privacy)'na uygun olmalıdır.
> Geliştiriciler, son kullanıcılar tarafından bu aracın kötüye kullanımından kaynaklanan herhangi bir yasal sorun, zarar veya kayıptan sorumlu değildir.

---

## 🛠 Teknik Uygulama Notları (Geliştiriciler İçin)

> Genel kullanıcılar bu bölümü atlayabilir

### Mimari Genel Bakış
```
Kullanıcı Tarayıcısı → İstemci Tarafı Analiz Modülü → Telegram Herkese Açık Web Önizleme Arayüzü → Yapılandırılmış Veri Çıkarma → Sonuç İşleme
```

### Temel Teknik Yaklaşımlar
- Herkese açık web önizleme sayfalarından meta veri almak için uygun CORS proxy yapılandırması ile `fetch` API'sini kullanır
- Kaynak bağlantısı keşfi için Open Graph etiketlerini (`og:video`, `og:image`, `og:title` vb.) ayrıştırır
- Medya bilgilerini tamamlamak için önizleme sayfalarındaki yapılandırılmış verileri (JSON-LD / Microdata) kullanır
- Sağlam bağlantı tanıma için regex kalıpları + DOM ayrıştırma ile çift doğrulama uygular

### Kendi Sunucunuzda Barındırma Kılavuzu (Referans)
```bash
# 1. Depoyu klonlayın (örnek)
git clone https://github.com/yourname/telegram-downloader-tu.git

# 2. Statik dosyaları dağıtın (HTTPS şiddetle önerilir)
#    - Vercel / Netlify / Cloudflare Pages (kolay kurulum, önerilir)
#    - Nginx + Let's Encrypt sertifikası (kendi kendine barındırma seçeneği)

# 3. Güvenlik başlıkları yapılandırma örneği (Nginx)
add_header Content-Security-Policy "default-src 'self'; script-src 'self' 'unsafe-inline';";
add_header X-Content-Type-Options "nosniff";
add_header Referrer-Policy "strict-origin-when-cross-origin";
add_header X-Frame-Options "DENY";
```

> 🔐 Üretim Ortamı Dağıtımı İçin En İyi Uygulamalar:
> - Ortadaki adam saldırılarını önlemek için her zaman HTTPS'yi etkinleştirin
> - Kötüye kullanımı ve aşırı istekleri önlemek için hız sınırlama (rate limiting) uygulayın
> - Kötüye kullanılabilecek hassas analiz mantığını ifşa etmekten kaçının
> - Güvenlik yamalarını uygulamak için bağımlılıkları düzenli olarak gözden geçirin ve güncelleyin

---

## 🤝 Katkıda Bulunma

Bu eğitim projesini geliştirmeye yardımcı olmak için topluluk katkılarını memnuniyetle karşılıyoruz!

| Katkı Türü | Örnekler |
|-----------|----------|
| 🐛 Hata Bildirimleri | Ayrıntılı adımlarla Sorun oluşturun: URL + tarayıcı bilgisi + yeniden üretim adımları |
| 💡 Özellik Önerileri | UX iyileştirmeleri, erişilebilirlik veya yeni eğitim özellikleri için yapıcı fikirler paylaşın |
| 🌍 Çeviri Yardımı | Arayüz metninin ek dillere çevrilmesine yardımcı olun |
| 📚 Dokümantasyon | Kullanım örnekleri, teknik diyagramlar veya uyumluluk kılavuzları ekleyin |

> Bu proje [MIT Lisansı](./LICENSE) altında yayınlanmaktadır. Eğitim ve araştırma amaçları için özgürce kullanım ve değişikliği teşvik ediyoruz. Ticari özelleştirme talepleri için lütfen ayrı kanallar üzerinden bizimle iletişime geçin.

---

## ❓ Sıkça Sorulan Sorular (SSS)

**S: "İçerik alınamadı" mesajı neden görünüyor?**  
C: Olası nedenler: ① Bağlantı özel bir kanala/gruba veya kimlik doğrulama gerektiren içeriği işaret ediyor ② İçerik silinmiş veya "Yalnızca üyeler için" olarak ayarlanmış ③ Telegram web önizleme yapısını geçici olarak değiştirdi ④ Ağ kısıtlamaları veya CORS sorunları. Çözüm: Herkese açık durumu doğrulayın → Farklı bir ağda deneyin → Bekleyip tekrar deneyin.

**S: İndirilen video/görselde filigran var mı?**  
C: Bu araç, Telegram'ın resmi altyapısı tarafından sağlanan orijinal kaynak URL'lerini döndürür. Filigran varlığı tamamen içeriği yükleyen kullanıcının ayarlarına bağlıdır. Bu araç herhangi bir filigran veya gömülü işaret eklemez, kaldırmaz veya değiştirmez.

**S: Kanal/grup mesaj geçmişi için toplu işleme destekleniyor mu?**  
C: Mevcut sürüm, kararlılık ve uyumluluğu önceliklendirmek için tek mesaj analizine odaklanmaktadır. Toplu işlemler için, lütfen önce kullanım durumunuzun Telegram'ın [Kullanım Şartları](https://telegram.org/tos) ile hız sınırları ve veri kullanımı konusunda uyumlu olduğundan emin olun.

**S: Bu araç kullanım verilerimi veya Telegram hesap bilgilerimi topluyor mu?**  
C: Hayır. Bu, arka uç günlüğü, analiz komut dosyaları, çerez tabanlı izleme veya hesap bağlantısı içermeyen tamamen statik bir ön uç projesidir. Tüm işleme, tarayıcı oturumunuz içinde yerel olarak gerçekleşir ve herhangi bir giriş gerekmez.

**S: Özel sohbetleri veya kişisel konuşmaları analiz edebilir mi?**  
C: Hayır. Bu araç yalnızca **herkese açık kanallardan/gruplardan web önizleme bağlantılarını** destekler. Özel sohbetlerin, kişisel konuşmaların veya giriş gerektiren içeriklerin analizi teknik olarak desteklenmez ve etik olarak önerilmez. Bu, kullanıcı gizliliğine ve ürün uyumluluğuna olan temel bağlılığımızı yansıtır.

---

## 🌱 Felsefemiz

> Teknolojinin kendisi nötrdür. Önemli olan, onu kullananların *niyeti* ve *sorumluluğudur*.

Geliştiricileri ve kullanıcıları bu değerleri benimsemeye davet ediyoruz:

- 🔬 Merak ve etik öğrenme yoluyla web teknolojilerini daha derinlemesine anlamaya çalışmak
- 🤲 Kaynakları doğru şekilde belirterek ve izin alarak yaratıcıların haklarına ve kullanıcı gizliliğine saygı göstermek
- 🌍 İnovasyon ile kültürel mirasın korunması arasında denge kuran sağlıklı bir dijital ekosisteme katkıda bulunmak
- ⚖️ Teknik keşif ile yasal uyumluluk arasında denge kurarak sorumlu geliştirme pratiği yapmak

Birlikte, yaratıcılık, paylaşım ve teknolojinin sorumlu kullanımının olumlu bir döngüsünü teşvik edelim ✨

---

## 📄 Lisans

Bu proje [MIT Lisansı](./LICENSE) altında dağıtılmaktadır.

```
Copyright (c) 2026 Telegram Media Analyzer Project

Bu yazılımın ve ilişkili belgelendirme dosyalarının ("Yazılım") bir kopyasını
elde eden herhangi bir kişiye, aşağıdaki koşullar altında, Yazılımı
kullanma, kopyalama, değiştirme, birleştirme, yayınlama, dağıtma,
alt lisanslama ve/veya satma hakları ücretsiz olarak verilir:

Yukarıdaki telif hakkı bildirimi ve bu izin bildirimi, Yazılımın tüm
kopyalarında veya önemli bölümlerinde yer almalıdır.

YAZILIM "OLDUĞU GİBİ" SUNULMAKTADIR, AÇIK VEYA ZIMNİ OLARAK,
TİCARİ OLABİLİRLİK, BELİRLİ BİR AMACA UYGUNLUK VE İHLAL ETMEME
GARANTİLERİ DAHİL ANCAK BUNLARLA SINIRLI OLMAMAK ÜZERE HERHANGİ BİR
GARANTİ İÇERMEZ. HİÇBİR DURUMDA YAZARLAR VEYA TELİF HAKKI SAHİPLERİ,
SÖZLEŞME, HAKSIZ FİİL VEYA BAŞKA BİR ŞEKİLDE, YAZILIMDAN VEYA
YAZILIMIN KULLANIMINDAN VEYA YAZILIMLA İLGİLİ DİĞER İŞLEMLERDEN
KAYNAKLANAN HERHANGİ BİR TALEP, ZARAR VEYA DİĞER SORUMLULUKTAN
SORUMLU OLMAYACAKTIR.
```

---

*📅 Son Güncelleme: Mayıs 2026*  
*🔖 Sürüm: v1.2.0-tr (Ön uç optimizasyonu / Geliştirilmiş uyumluluk dokümantasyonu / Geliştirilmiş gizlilik koruması)*