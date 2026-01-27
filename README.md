# AI Prompt: https://claude.ai/share/e9089ef5-a6c8-49c8-8984-c99f1852ea64



[![github-follow](https://img.shields.io/github/followers/Prajwal100?label=Follow&logoColor=purple&style=social)](https://github.com/Prajwal100)
[![GitHub stars](https://img.shields.io/github/stars/Prajwal100/Complete-Ecommerce-in-laravel-10.svg?style=social)](https://github.com/Prajwal100/Complete-Ecommerce-in-laravel-10/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Prajwal100/Complete-Ecommerce-in-laravel-10.svg)](https://github.com/Prajwal100/Complete-Ecommerce-in-laravel-10/network)
[![license](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://choosealicense.com/licenses/mit/)
[![Buy Me A Coffee](https://img.shields.io/badge/Support-Buy%20Me%20A%20Coffee-yellow?style=flat-square&logo=buy-me-a-coffee)](https://buymeacoffee.com/prajwalrai/support-my-work-complete-laravel-e-commerce-project)

# 🚀 Complete E-commerce Website in Laravel 10
A full-fledged **eCommerce solution** built on **Laravel 10**, featuring a modern UI, powerful admin panel, seamless payment integration, and a user-friendly shopping experience.

---

## 🎥 Live Demo & Tutorials
🔹 **Setup Video:** [Watch Here](https://www.youtube.com/watch?v=URX5D1A5XQ4&t=19s)
🔹 **Demo Video:** [Live Demo](https://youtu.be/RxyrQQ3oTIE?si=Iq25IuJ8_eB5OJpC)
🔹 **Complete Tutorial Series:** [Watch Now](https://www.youtube.com/watch?v=FdAMucaks64&list=PLIFG3IUe1Zxo8Zvju3_kJJvoKSaIP_SC_&index=1&t=44s)

---

## 🌟 Features

### 🔹 **Frontend**
- ⚡ **Progressive Web App (PWA) support**
- 🎨 **Modern & responsive design**
- 🛒 **Shopping cart, wishlist, and order tracking**
- 🔎 **SEO-friendly URLs & metadata**
- 💳 **Integrated PayPal payment gateway**
- 📢 **Social login (Google, Facebook, Github)**
- 💬 **Multi-level comments & reviews**

### 🔹 **Admin Dashboard**
- 🎛️ **Role management**
- 📊 **Advanced analytics & reporting**
- 🛍️ **Product & order management**
- 🔔 **Real-time notifications & messaging**
- 🏷️ **Coupon & discount system**
- 📰 **Blog & category management**
- 📸 **Media & banner manager**

### 🔹 **User Dashboard**
- 📦 **Order history & tracking**
- 💬 **Review & comment system**
- 🔧 **Profile customization**

---

## 🛠️ Installation Guide

### 🔹 **Step 1: Clone the Repository**
```sh
git clone https://github.com/Prajwal100/Complete-Ecommerce-in-laravel-10.git
cd Complete-Ecommerce-in-laravel-10
```

### 🔹 **Step 2: Install Dependencies**
```sh
composer install
npm install
```

### 🔹 **Step 3: Environment Setup**
```sh
cp .env.example .env
php artisan key:generate
```
Update `.env` with database credentials.

### 🔹 **Step 4: Database Configuration**
```sh
php artisan migrate --seed
```
Import `database/e-shop.sql` into your database manually (if needed).

### 🔹 **Step 5: Setup Storage**
```sh
php artisan storage:link
```

### 🔹 **Step 6: Run the Application**
```sh
php artisan serve
```
🔗 Open `http://localhost:8000`

### **Admin Login Credentials:**
📧 **Email:** `admin@gmail.com`  
🔑 **Password:** `1111`

---

## 🎙️ Transform Text into Speech with NepVox! 🔊
🚀 **[NepVox](https://nepvox.com/)** is an advanced **AI-powered text-to-speech** platform that helps you convert any text into natural human-like voice effortlessly.

✅ **Supports multiple languages & voices**
✅ **Perfect for videos, accessibility & podcasts**
✅ **Simple API integration for businesses**

🎧 **Experience it now:** [NepVox AI TTS](https://nepvox.com/)

---

## 📷 Screenshots

### **Admin Panel**
![Admin](https://user-images.githubusercontent.com/29488275/90719413-13b82200-e2d4-11ea-8ca0-f0e5551c4c9d.png)

### **Product Management**
![Products](https://user-images.githubusercontent.com/29488275/90719534-61348f00-e2d4-11ea-8a81-409daee0ad94.png)

### **User Dashboard**
![User Dashboard](https://user-images.githubusercontent.com/29488275/90719563-7a3d4000-e2d4-11ea-9e6a-56caac13b146.png)

---

## 📩 Contact Me
💼 Need a **Full Stack Laravel Developer**? Let's work together!

📧 **Email:** Prajwal.iar@gmail.com  
📲 **WhatsApp:** +977-9818441226  

🔗 **[Hire Me on Upwork](https://www.upwork.com/freelancers/~01210bb2575a8c05a9)**

### ☕ Support My Work
If you find this project helpful, consider [buying me a coffee](https://buymeacoffee.com/prajwalrai/support-my-work-complete-laravel-e-commerce-project). Your support helps maintain and improve this project! 🚀

---

## 📜 License
🔹 This project is **MIT Licensed** – Feel free to use & modify!

⭐ **If you find this project helpful, don't forget to star it!** ⭐

# E-Commerce Laravel 10 - Tes Teknis Magang

Project ini berbasis [Complete-Ecommerce-in-laravel-10](https://github.com/Prajwal100/Complete-Ecommerce-in-laravel-10) dengan penambahan fitur sebagai bagian dari tes teknis magang.

## Instalasi

1. Clone repository
```bash
git clone https://github.com/Prajwal100/Complete-Ecommerce-in-laravel-10.git
cd Complete-Ecommerce-in-laravel-10
```

2. Install dependencies
```bash
composer install
npm install
```

3. Setup environment
```bash
cp .env.example .env
php artisan key:generate
```

4. Konfigurasi database di file `.env`

5. Jalankan migrations dan seeders
```bash
php artisan migrate --seed
```

6. Jalankan aplikasi
```bash
php artisan serve
```

---

## Catatan Implementasi

### Task 5: Menambahkan Daftar Produk di Halaman Detail Order

**Yang Diubah:**
- Membuat migration baru untuk menambahkan kolom `product_name` dan `product_photo` ke tabel `carts`
- Update model `Cart` untuk memasukkan field baru ke dalam `$fillable`
- Memodifikasi tampilan detail order (`resources/views/user/order/show.blade.php`) untuk menampilkan tabel daftar produk yang komprehensif dengan informasi:
  - Gambar produk
  - Nama produk
  - Harga satuan
  - Jumlah/quantity
  - Total harga per item
  - Ringkasan order (subtotal, ongkir, grand total)

**Alasan:**
- Halaman detail order yang asli hanya menampilkan informasi order dan data pengiriman, tapi tidak menampilkan produk apa saja yang dibeli
- Ini menyulitkan user untuk mereview apa yang mereka beli
- Menambahkan daftar produk meningkatkan user experience dan transparansi order

**File yang Dimodifikasi:**
- `database/migrations/XXXX_add_product_snapshot_to_carts_table.php` (dibuat baru)
- `app/Models/Cart.php`
- `resources/views/user/order/show.blade.php`

---

### Task 6: Mempertahankan Data Produk Order Ketika Produk Diupdate/Dihapus

**Yang Diubah:**
- Mengimplementasikan mekanisme "snapshot" yang menyimpan informasi produk pada saat order dibuat
- Memodifikasi method `OrderController@store` untuk menangkap dan menyimpan:
  - Nama produk (`product_name`)
  - Foto produk (`product_photo`)
- Field-field ini disimpan bersamaan dengan field `price` yang sudah ada di tabel `carts` ketika order dibuat

**Alasan:**
- Sebelumnya, halaman detail order menampilkan informasi produk dengan melakukan query langsung ke tabel `products` melalui relasi
- Hal ini menyebabkan masalah ketika:
  - Admin mengupdate nama produk, harga, atau gambar → history order menampilkan informasi yang salah
  - Admin menghapus produk → halaman detail order error dengan null reference
- Dengan melakukan snapshot data produk saat order dibuat, kita memastikan:
  - Akurasi histori: order selalu menampilkan apa yang benar-benar dibeli customer
  - Integritas data: detail order tetap utuh meskipun produk dimodifikasi atau dihapus
  - Kepatuhan: penting untuk keperluan accounting, dispute, dan legal

**Pendekatan Implementasi:**
```php
// Di OrderController@store, setelah order disimpan:
$carts = Cart::where('user_id', auth()->user()->id)
    ->where('order_id', null)
    ->get();

foreach ($carts as $cart) {
    $product = $cart->product;
    $cart->order_id = $order->id;
    
    if ($product) {
        $cart->product_name = $product->title;
        $cart->product_photo = $product->photo;
    }
    
    $cart->save();
}
```

**File yang Dimodifikasi:**
- `app/Http/Controllers/OrderController.php`
- `app/Models/Cart.php`
- `resources/views/user/order/show.blade.php`

---

## Hasil Testing

### Sebelum Produk Diedit/Dihapus
![Detail Order Sebelum](screenshots/screenshot_before.png)
*Detail order menampilkan informasi produk dengan data asli*

### Setelah Produk Diedit/Dihapus
![Detail Order Setelah](screenshots/screenshot_after.png)
*Detail order tetap tidak berubah meskipun produk sudah dimodifikasi/dihapus*

**Skenario Testing:**
1. Membuat order dengan sebuah produk (misal: "Laptop ABC" dengan harga $111.60)
2. Memverifikasi halaman detail order menampilkan informasi produk yang benar
3. Sebagai admin, mengedit produk tersebut (mengubah nama menjadi "Laptop XYZ" dan harga menjadi $200.00)
4. Kembali ke halaman detail order
5. **Hasil:** Order masih menampilkan "Laptop ABC" dengan harga $111.60 (snapshot terjaga)

---

## Saran & Perbaikan

### 1. **Desain Database**

**Masalah:** Tabel `carts` digunakan untuk active shopping cart DAN historical order items sekaligus
- Ini membuat bingung dan berpotensi masalah integritas data
- Nama tabel "carts" tidak mencerminkan fungsi gandanya

**Saran:**
- Buat tabel `order_items` khusus untuk order yang sudah selesai
- Tabel `carts` hanya untuk shopping session yang aktif
- Struktur migration:
```php
Schema::create('order_items', function (Blueprint $table) {
    $table->id();
    $table->foreignId('order_id')->constrained()->onDelete('cascade');
    $table->foreignId('product_id')->nullable(); // nullable karena produk bisa dihapus
    $table->string('product_name');
    $table->string('product_photo')->nullable();
    $table->decimal('price', 10, 2);
    $table->integer('quantity');
    $table->decimal('amount', 10, 2);
    $table->timestamps();
});
```

**Manfaat:**
- Pemisahan fungsi yang jelas
- Performa query lebih baik (tidak perlu filter `order_id IS NULL` untuk cart aktif)
- Lebih mudah dipahami dan di-maintain

---

### 2. **Kualitas Kode & Konsistensi**

**Masalah yang Ditemukan:**
- Penamaan relasi tidak konsisten: `cart_info()` vs `cart()` di model Order
- Penggunaan string class name (`'App\Models\Cart'`) dan class-based import (`Cart::class`) yang tercampur
- Banyak kode yang di-comment di beberapa file (misal: model Cart, OrderController)

**Saran:**
- Gunakan penamaan yang konsisten: rename `cart_info()` menjadi `orderItems()` atau `items()`
- Selalu gunakan syntax `Cart::class` daripada string class name
- Hapus kode yang di-comment atau tambahkan dokumentasi yang menjelaskan kenapa disimpan
- Contoh refactor:
```php
// Daripada:
public function cart_info(){
    return $this->hasMany('App\Models\Cart','order_id','id');
}

// Gunakan:
public function items(){
    return $this->hasMany(Cart::class, 'order_id');
}
```

---

### 3. **Error Handling**

**Masalah:** Aplikasi crash ketika mengakses order dengan data relasi yang hilang (misal: shipping method yang dihapus)

**Error saat ini:** `Attempt to read property "price" on null` ketika `$order->shipping` bernilai null

**Saran:**
- Tambahkan null check di view:
```blade
{{ $order->shipping?->price ?? 'N/A' }}
```
- Atau handle di level controller:
```php
public function show($id)
{
    $order = Order::with(['cart_info', 'shipping'])->findOrFail($id);
    
    // Tambahkan default value untuk relasi yang hilang
    if (!$order->shipping) {
        $order->shipping = new \stdClass();
        $order->shipping->price = 0;
    }
    
    return view('user.order.show', compact('order'));
}
```

---

### 4. **Snapshot Produk - Field Tambahan**

**Keterbatasan saat ini:** Hanya `product_name` dan `product_photo` yang di-snapshot

**Saran:** Snapshot field produk tambahan yang berguna untuk catatan histori:
- `product_sku` - untuk tracking inventory
- `product_category` - untuk reporting dan analitik
- `product_description` - untuk referensi customer
- `product_brand` - penting untuk produk bermerek

**Implementasi:**
```php
// Di migration
$table->string('product_sku')->nullable();
$table->string('product_category')->nullable();

// Di OrderController
$cart->product_sku = $product->sku;
$cart->product_category = $product->cat_info->title ?? null;
```

---

### 5. **Penyimpanan Gambar**

**Masalah:** Saat ini menyimpan full path gambar yang bisa rusak jika:
- File dipindahkan atau direname
- Struktur storage berubah
- Menggunakan cloud storage (S3, dll)

**Saran:**
- Simpan relative path daripada full path
- Pertimbangkan untuk copy gambar produk ke folder `order_snapshots` ketika order dibuat
- Ini memastikan gambar tetap tersimpan meskipun gambar produk asli dihapus
```php
// Contoh implementasi
$snapshotPath = 'order_snapshots/' . $order->id . '/';
Storage::copy($product->photo, $snapshotPath . basename($product->photo));
$cart->product_photo = $snapshotPath . basename($product->photo);
```

---

### 6. **Alur Status Order**

**Masalah:** Perubahan status order tidak di-log, sehingga sulit tracking histori order

**Saran:**
- Implementasikan tabel `order_status_history` untuk tracking semua perubahan status
- Include timestamp dan admin yang melakukan perubahan
- Ini penting untuk:
  - Investigasi customer service
  - Penyelesaian dispute
  - Metrik performa (waktu dari order sampai delivery)
```php
Schema::create('order_status_history', function (Blueprint $table) {
    $table->id();
    $table->foreignId('order_id')->constrained()->onDelete('cascade');
    $table->string('old_status')->nullable();
    $table->string('new_status');
    $table->foreignId('changed_by')->nullable()->constrained('users');
    $table->text('notes')->nullable();
    $table->timestamps();
});
```

---

### 7. **Manajemen Stok**

**Masalah:** Stok hanya dikurangi ketika status order berubah menjadi "delivered"

**Problem:** Banyak customer bisa memesan produk yang sama meskipun stok rendah, menyebabkan overselling

**Saran:**
- Reserve stok ketika order dibuat (status = "new")
- Kurangi stok ketika delivered
- Kembalikan stok jika order dibatalkan
- Implementasikan mekanisme inventory locking yang proper
```php
// Di OrderController@store
foreach ($carts as $cart) {
    $product = $cart->product;
    if ($product->stock < $cart->quantity) {
        throw new \Exception("Stok tidak cukup untuk {$product->title}");
    }
    // Reserve stok
    $product->stock -= $cart->quantity;
    $product->reserved_stock += $cart->quantity;
    $product->save();
}
```

---

### 8. **Perbaikan Keamanan**

**Masalah:**
- Tidak ada authorization check di halaman order show (user mana saja bisa lihat order siapa saja dengan mengubah URL)
- Informasi sensitif terekspos di detail order

**Saran:**
- Tambahkan authorization policy:
```php
// Di OrderController@show
public function show($id)
{
    $order = Order::findOrFail($id);
    
    // Pastikan user hanya bisa lihat order mereka sendiri (kecuali admin)
    if (auth()->user()->id !== $order->user_id && auth()->user()->role !== 'admin') {
        abort(403, 'Akses tidak diizinkan');
    }
    
    return view('user.order.show', compact('order'));
}
```

---

### 9. **Peningkatan User Experience**

**Saran:**
- Tambahkan notifikasi email ketika status order berubah
- Implementasi order tracking dengan status yang lebih detail (processing, shipped, out for delivery, delivered)
- Tambahkan estimasi tanggal pengiriman
- Izinkan customer untuk membatalkan order dalam jangka waktu tertentu
- Tambahkan sistem rating/review order setelah delivery

---

### 10. **Testing**

**Kondisi saat ini:** Tidak ada automated test

**Saran:**
- Tulis feature test untuk alur-alur kritis:
  - Pembuatan produk
  - Pembuatan order
  - Preservasi snapshot produk
  - Manajemen stok
- Contoh test:
```php
public function test_order_mempertahankan_data_produk_setelah_dihapus()
{
    $product = Product::factory()->create(['title' => 'Nama Asli']);
    // Buat order dengan produk
    // Hapus produk
    // Assert order masih menampilkan 'Nama Asli'
}
```

---

## Kesimpulan

Implementasi berhasil memenuhi requirement yang diminta:
- ✅ Halaman detail order sekarang menampilkan daftar produk dengan gambar dan detail lengkap
- ✅ Data order tetap terjaga meskipun produk diupdate atau dihapus
- ✅ Solusi mempertahankan integritas data dan akurasi histori

Saran-saran di atas bertujuan untuk meningkatkan kualitas kode, maintainability, dan user experience untuk pengembangan ke depannya.

---

## Pembuat

Tes diselesaikan oleh: Zabriel Briano  
Tanggal: 20 Januari 2026  
