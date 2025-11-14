#Tugas Create Multimedia Client Server Kodi #

Pertama install Kodi dengan menggunakan kode ini

``` bash
lsb_release -d
```

```bash
apt update ; apt install kodi -y
```

masukan prompt berikut untuk memastikan kodi sudah terinstall dengan baik

```bash
kodi -version
```

Jika sudah, buka aplikasi Kodi, 

```bash
kodi
```

lalu masuk ke menu Setting dan pilih menu Services


Pada bagian UPnP / DLNA, aktifkan menu Enable UPnP Support dan Share My Libraries 

Masih di menu Services, pilih di SMB Client, lalu pada menu Minimum Protocol Version ubah menjadi SMBv1

Lalu install Samba sebagai penghubung antar device menggunakan prompt ini

Lalu siapkan file yang akan ditambahkan pada Kodi, seperti file musik yang diisi oleh musik musik yang akan dimasukkan ke menu Music dan file video yang akan dimasukkan pada menu Video

Buka kembali Kodi kembali, masukkan musik dengan mengklik menu Music, pilih Files, lalu pilih Add Music, lalu klik Browse untuk memilih file yang telah dibuat sebelumnya untuk memasukkan file tersebut ke dalam Kodi

Lakukan ini juga untuk memasukkan video, music video, dsb

Jika sudah, download VLC pada device ke dua. Pilih jaringan lokal yang tersedia, lalu pilih nama server Kodi pada device yang pertama dan kalian bisa melihat isi file yang terdapat pada server tersebut.


