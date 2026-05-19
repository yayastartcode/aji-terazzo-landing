<svelte:head>
  <title>Aji Terazzo | Jasa Pembuatan, Pasang & Poles Terazzo Bali Lombok</title>
  <meta
    name="description"
    content="Aji Terazzo melayani pembuatan, pemasangan, dan poles terazzo untuk rumah, villa, cafe, hotel, dan proyek interior di Bali dan Lombok."
  />
</svelte:head>

<script>
  const phone = '6287777504122';
  const waText = encodeURIComponent('Halo Aji Terazzo, saya mau konsultasi jasa pembuatan/pasang/poles terazzo.');
  const waLink = `https://wa.me/${phone}?text=${waText}`;
  const instagramLink = 'https://instagram.com/terazzo_bali_lombok';

  const services = [
    {
      title: 'Jasa Pembuatan Terazzo',
      desc: 'Rancang permukaan terazzo custom untuk lantai, meja, wastafel, tangga, hingga elemen dekoratif.',
      tag: 'Custom motif & warna'
    },
    {
      title: 'Pasang Terazzo',
      desc: 'Pemasangan rapi untuk rumah, villa, cafe, hotel, kantor, dan proyek interior komersial.',
      tag: 'Rapi, presisi, siap proyek'
    },
    {
      title: 'Poles Terazzo',
      desc: 'Menghidupkan kembali kilap terazzo lama agar terlihat bersih, halus, dan premium lagi.',
      tag: 'Restorasi & finishing'
    }
  ];

  const steps = [
    'Konsultasi kebutuhan, lokasi, dan ukuran area',
    'Rekomendasi motif, warna, finishing, dan estimasi pengerjaan',
    'Pembuatan atau pemasangan oleh tim lapangan',
    'Poles akhir sampai permukaan terlihat bersih dan elegan'
  ];

  const gallerySlots = [
    {
      title: 'Lantai terazzo poles glossy',
      note: 'Permukaan cream dengan chip halus dan refleksi bersih',
      src: '/gallery/terazzo-polished-floor-01.jpg',
      alt: 'Lantai terazzo cream yang sudah dipoles mengkilap di area interior modern'
    },
    {
      title: 'Wastafel terazzo minimalis',
      note: 'Basin putih speckled dengan fixture hitam modern',
      src: '/gallery/terazzo-vanity-basin-01.jpg',
      alt: 'Wastafel terazzo putih minimalis dengan faucet hitam dan dekorasi bathroom modern'
    },
    {
      title: 'Vanity kayu dan basin terazzo',
      note: 'Kombinasi warm wood, motif terazzo, dan tanaman hijau',
      src: '/gallery/terazzo-wood-vanity-01.jpg',
      alt: 'Vanity kayu dengan wastafel terazzo putih bermotif chip warna hangat dan tanaman hijau'
    },
    {
      title: 'Bathroom vanity terazzo',
      note: 'Finishing lantai, backsplash, dan vanity untuk ruang mandi premium',
      src: '/gallery/terazzo-project-04.jpg',
      alt: 'Bathroom modern dengan lantai dan backsplash terazzo, vanity kayu, cermin bulat, dan toilet dinding'
    },
    {
      title: 'Floating vanity terazzo',
      note: 'Meja wastafel putih dengan chip warna dan frame hitam',
      src: '/gallery/terazzo-project-05.jpg',
      alt: 'Floating vanity terazzo putih dengan sink rectangular, faucet dinding, dan frame metal hitam'
    },
    {
      title: 'Countertop terazzo panjang',
      note: 'Permukaan putih glossy untuk island interior dekat area kaca',
      src: '/gallery/terazzo-project-06.jpg',
      alt: 'Countertop terazzo putih glossy panjang dengan shelving built-in di interior dekat jendela besar'
    }
  ];

  const faqs = [
    {
      q: 'Bisa untuk villa, cafe, atau hotel?',
      a: 'Bisa. Landing ini disiapkan untuk kebutuhan residensial maupun proyek komersial seperti villa, cafe, resto, hotel, dan interior boutique.'
    },
    {
      q: 'Apakah bisa poles terazzo lama?',
      a: 'Bisa. Aji Terazzo melayani poles dan finishing ulang agar permukaan terazzo lama terlihat lebih bersih, halus, dan layak tampil.'
    },
    {
      q: 'Area layanan di mana?',
      a: 'Fokus layanan untuk Bali dan Lombok. Untuk lokasi lain, bisa konsultasi dulu via WhatsApp.'
    },
    {
      q: 'Bagaimana cara cek harga?',
      a: 'Kirim foto area, ukuran perkiraan, lokasi proyek, dan jenis layanan yang dibutuhkan lewat WhatsApp.'
    }
  ];
</script>

<main class="min-h-screen bg-[#f4eadc] text-[#2d241d]">
  <section class="relative overflow-hidden terrazzo-grain">
    <div class="absolute inset-0 bg-[linear-gradient(125deg,rgba(244,234,220,.96),rgba(248,241,230,.84)_45%,rgba(45,36,29,.08))]"></div>
    <div class="absolute -right-24 top-20 h-72 w-72 rounded-full bg-[#d88b4a]/20 blur-3xl"></div>
    <div class="absolute -left-24 bottom-10 h-80 w-80 rounded-full bg-[#215452]/20 blur-3xl"></div>

    <nav class="relative z-10 mx-auto flex max-w-7xl items-center justify-between px-5 py-5 md:px-8">
      <a href="#top" class="flex items-center gap-3" aria-label="Aji Terazzo home">
        <span class="grid h-11 w-11 place-items-center rounded-full bg-[#2d241d] text-lg font-black text-[#f8f1e6] shadow-xl">AT</span>
        <span>
          <span class="block text-sm font-black uppercase tracking-[.22em] text-[#215452]">Aji Terazzo</span>
          <span class="block text-xs text-[#6f6255]">Bali - Lombok</span>
        </span>
      </a>
      <div class="hidden items-center gap-7 text-sm font-bold text-[#5b4c40] md:flex">
        <a class="hover:text-[#215452]" href="#layanan">Layanan</a>
        <a class="hover:text-[#215452]" href="#galeri">Galeri</a>
        <a class="hover:text-[#215452]" href="#proses">Proses</a>
        <a class="hover:text-[#215452]" href="#faq">FAQ</a>
      </div>
      <a
        href={waLink}
        class="rounded-full bg-[#215452] px-4 py-3 text-sm font-black text-white shadow-lg shadow-[#215452]/20 transition hover:-translate-y-0.5 hover:bg-[#163b3a]"
      >Chat WA</a>
    </nav>

    <div class="relative z-10 mx-auto max-w-5xl px-5 pt-3 md:px-8">
      <div class="mx-auto overflow-hidden rounded-[1.75rem] border border-[#2d241d]/10 bg-white/65 p-2 shadow-2xl shadow-[#2d241d]/10 backdrop-blur">
        <img
          src="/brand/aji-terazzo-banner.jpg"
          alt="Banner Aji Terazzo, jasa pembuatan, pasang, dan poles terazzo"
          class="mx-auto w-full rounded-[1.35rem] object-cover"
        />
      </div>
    </div>

    <div id="top" class="relative z-10 mx-auto grid max-w-7xl gap-10 px-5 pb-20 pt-10 md:grid-cols-[1.08fr_.92fr] md:px-8 md:pb-28 md:pt-16">
      <div class="reveal-up max-w-3xl">
        <div class="mb-6 inline-flex items-center gap-2 rounded-full border border-[#d8b58d] bg-white/55 px-4 py-2 text-sm font-bold text-[#6e4b32] shadow-sm backdrop-blur">
          <span class="h-2 w-2 rounded-full bg-[#d88b4a]"></span>
          Spesialis terazzo untuk rumah, villa, cafe & proyek interior
        </div>
        <h1 class="max-w-4xl text-5xl font-black leading-[.95] tracking-[-.06em] text-[#2d241d] md:text-7xl lg:text-8xl">
          Terazzo custom yang bikin ruang terlihat mahal.
        </h1>
        <p class="mt-7 max-w-2xl text-lg leading-8 text-[#604f42] md:text-xl">
          Aji Terazzo melayani jasa pembuatan, pasang, dan poles terazzo untuk area Bali dan Lombok. Cocok untuk lantai, meja, wastafel, tangga, villa, cafe, hotel, dan interior premium.
        </p>
        <div class="mt-9 flex flex-col gap-3 sm:flex-row">
          <a
            href={waLink}
            class="group rounded-full bg-[#d88b4a] px-7 py-4 text-center text-base font-black text-[#281d16] shadow-xl shadow-[#d88b4a]/30 transition hover:-translate-y-1 hover:bg-[#c97834]"
          >Konsultasi via WhatsApp <span class="inline-block transition group-hover:translate-x-1">-></span></a>
          <a
            href={instagramLink}
            target="_blank"
            rel="noreferrer"
            class="rounded-full border border-[#2d241d]/15 bg-white/60 px-7 py-4 text-center text-base font-black text-[#2d241d] backdrop-blur transition hover:-translate-y-1 hover:bg-white"
          >Lihat Instagram</a>
        </div>
        <div class="mt-10 grid max-w-2xl grid-cols-3 overflow-hidden rounded-[2rem] border border-[#2d241d]/10 bg-white/55 shadow-sm backdrop-blur">
          <div class="p-4">
            <strong class="block text-2xl font-black text-[#215452]">3</strong>
            <span class="text-xs font-bold text-[#6f6255]">Layanan inti</span>
          </div>
          <div class="border-x border-[#2d241d]/10 p-4">
            <strong class="block text-2xl font-black text-[#215452]">2</strong>
            <span class="text-xs font-bold text-[#6f6255]">Area fokus</span>
          </div>
          <div class="p-4">
            <strong class="block text-2xl font-black text-[#215452]">WA</strong>
            <span class="text-xs font-bold text-[#6f6255]">Fast response</span>
          </div>
        </div>
      </div>

      <div class="relative min-h-[520px] reveal-up md:min-h-0" style="animation-delay: 140ms;">
        <div class="absolute left-4 top-0 h-[460px] w-[78%] rotate-[-7deg] rounded-[3rem] bg-[#2d241d] shadow-2xl md:left-8"></div>
        <div class="float-slow absolute right-0 top-12 w-[86%] overflow-hidden rounded-[3rem] border-[10px] border-[#f8f1e6] bg-[#d8c5ad] shadow-2xl">
          <div class="aspect-[4/5] terrazzo-grain bg-[#cbb69b]"></div>
          <div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_20%,rgba(255,255,255,.48),transparent_28%),linear-gradient(to_top,rgba(45,36,29,.78),transparent_45%)]"></div>
          <div class="absolute bottom-0 p-7 text-white">
            <p class="text-sm font-bold uppercase tracking-[.22em] text-[#f6d6a9]">Finishing premium</p>
            <h2 class="mt-2 text-3xl font-black leading-tight">Permukaan halus, motif hidup, karakter kuat.</h2>
          </div>
        </div>
        <div class="absolute bottom-8 left-0 max-w-[260px] rounded-[2rem] bg-white p-5 shadow-2xl">
          <p class="text-sm font-black text-[#215452]">Estimasi cepat</p>
          <p class="mt-1 text-sm leading-6 text-[#67584a]">Kirim foto area + ukuran, kami bantu arahkan jenis pengerjaan yang pas.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="layanan" class="px-5 py-20 md:px-8">
    <div class="mx-auto max-w-7xl">
      <div class="max-w-3xl">
        <p class="text-sm font-black uppercase tracking-[.24em] text-[#b06d36]">Layanan Aji Terazzo</p>
        <h2 class="mt-3 text-4xl font-black tracking-[-.04em] md:text-6xl">Dari bikin baru sampai poles ulang.</h2>
      </div>
      <div class="mt-10 grid gap-5 md:grid-cols-3">
        {#each services as service, index}
          <article class="group rounded-[2rem] border border-[#2d241d]/10 bg-[#fffaf2] p-6 shadow-sm transition hover:-translate-y-2 hover:shadow-2xl">
            <div class="mb-7 flex items-center justify-between">
              <span class="rounded-full bg-[#215452]/10 px-3 py-1 text-xs font-black uppercase tracking-[.14em] text-[#215452]">{service.tag}</span>
              <span class="text-4xl font-black text-[#d8b58d]">0{index + 1}</span>
            </div>
            <h3 class="text-2xl font-black tracking-[-.03em]">{service.title}</h3>
            <p class="mt-4 leading-7 text-[#665749]">{service.desc}</p>
          </article>
        {/each}
      </div>
    </div>
  </section>

  <section class="bg-[#2d241d] px-5 py-20 text-[#fff7ec] md:px-8">
    <div class="mx-auto grid max-w-7xl gap-12 md:grid-cols-[.85fr_1.15fr]">
      <div>
        <p class="text-sm font-black uppercase tracking-[.24em] text-[#d8b58d]">Cocok untuk siapa?</p>
        <h2 class="mt-3 text-4xl font-black tracking-[-.04em] md:text-6xl">Untuk ruang yang butuh karakter, bukan lantai biasa.</h2>
      </div>
      <div class="grid gap-4 sm:grid-cols-2">
        {#each ['Villa & penginapan', 'Cafe & restoran', 'Rumah tinggal', 'Hotel & lobby', 'Meja & wastafel', 'Tangga & area dekoratif'] as item}
          <div class="rounded-[1.5rem] border border-white/10 bg-white/7 p-5 text-lg font-black backdrop-blur">
            {item}
          </div>
        {/each}
      </div>
    </div>
  </section>

  <section id="galeri" class="px-5 pb-20 md:px-8">
    <div class="mx-auto max-w-7xl">
      <div class="grid gap-8 md:grid-cols-[.9fr_1.1fr] md:items-end">
        <div>
          <p class="text-sm font-black uppercase tracking-[.24em] text-[#b06d36]">Galeri proyek</p>
          <h2 class="mt-3 text-4xl font-black tracking-[-.04em] md:text-6xl">Galeri hasil terazzo untuk inspirasi proyek kamu.</h2>
        </div>
        <p class="text-lg leading-8 text-[#665749]">
          Lihat contoh aplikasi terazzo untuk lantai, wastafel, vanity, countertop, dan area interior premium. Foto bisa terus ditambah sesuai portofolio terbaru.
        </p>
      </div>

      <div class="mt-10 grid gap-4 sm:grid-cols-2 lg:grid-cols-3">
        {#each gallerySlots as item, index}
          <article class="group overflow-hidden rounded-[2rem] border border-[#2d241d]/10 bg-[#fffaf2] shadow-sm transition hover:-translate-y-1 hover:shadow-2xl">
            <div class="relative aspect-[4/3] bg-[#d8c5ad]">
              <img src={item.src} alt={item.alt} loading="lazy" class="h-full w-full object-cover transition duration-700 group-hover:scale-105" />
              <div class="absolute inset-0 bg-gradient-to-t from-[#2d241d]/82 via-[#2d241d]/10 to-transparent"></div>
              <div class="absolute left-4 top-4 rounded-full bg-white/85 px-3 py-1 text-xs font-black uppercase tracking-[.14em] text-[#215452] backdrop-blur">Foto {index + 1}</div>
              <div class="absolute bottom-4 left-4 right-4 text-white">
                <h3 class="text-xl font-black tracking-[-.02em]">{item.title}</h3>
                <p class="mt-1 text-sm font-bold text-white/80">{item.note}</p>
              </div>
            </div>
          </article>
        {/each}
      </div>
    </div>
  </section>

  <section id="proses" class="px-5 py-20 md:px-8">
    <div class="mx-auto max-w-7xl">
      <div class="grid gap-10 md:grid-cols-[.9fr_1.1fr] md:items-start">
        <div class="sticky top-8">
          <p class="text-sm font-black uppercase tracking-[.24em] text-[#b06d36]">Alur kerja</p>
          <h2 class="mt-3 text-4xl font-black tracking-[-.04em] md:text-6xl">Mulai dari chat, lanjut survei atau estimasi.</h2>
          <a href={waLink} class="mt-8 inline-flex rounded-full bg-[#215452] px-7 py-4 font-black text-white shadow-lg transition hover:-translate-y-1 hover:bg-[#163b3a]">Tanya estimasi sekarang</a>
        </div>
        <div class="space-y-4">
          {#each steps as step, index}
            <div class="flex gap-5 rounded-[2rem] border border-[#2d241d]/10 bg-white/60 p-5 shadow-sm">
              <span class="grid h-12 w-12 shrink-0 place-items-center rounded-full bg-[#d88b4a] text-lg font-black text-[#2d241d]">{index + 1}</span>
              <p class="pt-2 text-lg font-bold leading-7 text-[#514438]">{step}</p>
            </div>
          {/each}
        </div>
      </div>
    </div>
  </section>

  <section class="px-5 pb-20 md:px-8">
    <div class="mx-auto max-w-7xl overflow-hidden rounded-[3rem] bg-[#215452] text-white shadow-2xl">
      <div class="grid md:grid-cols-[1.1fr_.9fr]">
        <div class="p-8 md:p-12">
          <p class="text-sm font-black uppercase tracking-[.24em] text-[#f6d6a9]">Butuh contoh hasil?</p>
          <h2 class="mt-3 text-4xl font-black tracking-[-.04em] md:text-6xl">Lihat update proyek dan motif di Instagram.</h2>
          <p class="mt-5 max-w-2xl text-lg leading-8 text-white/80">Untuk landing page final, bagian ini bisa diganti galeri foto proyek asli: sebelum-sesudah poles, detail motif, area lantai, meja, atau wastafel.</p>
          <a href={instagramLink} target="_blank" rel="noreferrer" class="mt-8 inline-flex rounded-full bg-[#f6d6a9] px-7 py-4 font-black text-[#2d241d] transition hover:-translate-y-1">@terazzo_bali_lombok</a>
        </div>
        <div class="min-h-[320px] terrazzo-grain bg-[#d8b58d]"></div>
      </div>
    </div>
  </section>

  <section id="faq" class="px-5 pb-20 md:px-8">
    <div class="mx-auto max-w-4xl">
      <p class="text-center text-sm font-black uppercase tracking-[.24em] text-[#b06d36]">FAQ</p>
      <h2 class="mt-3 text-center text-4xl font-black tracking-[-.04em] md:text-6xl">Pertanyaan sebelum mulai.</h2>
      <div class="mt-10 space-y-4">
        {#each faqs as faq}
          <details class="group rounded-[1.5rem] border border-[#2d241d]/10 bg-[#fffaf2] p-5 shadow-sm">
            <summary class="cursor-pointer list-none text-lg font-black marker:hidden">{faq.q}</summary>
            <p class="mt-3 leading-7 text-[#665749]">{faq.a}</p>
          </details>
        {/each}
      </div>
    </div>
  </section>

  <section class="px-5 pb-8 md:px-8">
    <div class="mx-auto max-w-7xl rounded-[3rem] bg-[#d88b4a] p-8 text-[#2d241d] md:p-12">
      <div class="grid gap-8 md:grid-cols-[1fr_auto] md:items-center">
        <div>
          <h2 class="text-4xl font-black tracking-[-.04em] md:text-6xl">Mau bikin atau poles terazzo?</h2>
          <p class="mt-4 max-w-2xl text-lg font-bold leading-8">Chat Aji Terazzo sekarang. Kirim foto area, ukuran perkiraan, dan lokasi proyek supaya estimasi lebih cepat.</p>
        </div>
        <a href={waLink} class="rounded-full bg-[#2d241d] px-8 py-5 text-center text-lg font-black text-white shadow-xl transition hover:-translate-y-1">WhatsApp 087777504122</a>
      </div>
    </div>
  </section>

  <footer class="px-5 pb-10 md:px-8">
    <div class="mx-auto flex max-w-7xl flex-col gap-4 border-t border-[#2d241d]/10 pt-8 text-sm font-bold text-[#6f6255] md:flex-row md:items-center md:justify-between">
      <p>© 2026 Aji Terazzo. Jasa pembuatan, pasang & poles terazzo.</p>
      <div class="flex gap-4">
        <a class="hover:text-[#215452]" href={waLink}>WhatsApp</a>
        <a class="hover:text-[#215452]" href={instagramLink} target="_blank" rel="noreferrer">Instagram</a>
      </div>
    </div>
  </footer>

  <a
    href={waLink}
    class="fixed bottom-5 right-5 z-50 flex h-16 w-16 items-center justify-center rounded-full bg-[#25D366] text-white shadow-2xl shadow-[#25D366]/35 ring-4 ring-white/70 transition hover:-translate-y-1 hover:scale-105 focus:outline-none focus:ring-4 focus:ring-[#128C7E]/40 md:bottom-7 md:right-7 md:h-[72px] md:w-[72px]"
    aria-label="Chat Aji Terazzo via WhatsApp"
  >
    <svg viewBox="0 0 32 32" class="h-9 w-9" aria-hidden="true" fill="currentColor">
      <path d="M19.11 17.47c-.28-.14-1.66-.82-1.92-.91-.26-.1-.45-.14-.64.14-.19.28-.73.91-.9 1.1-.17.19-.33.21-.61.07-.28-.14-1.18-.43-2.24-1.38-.83-.74-1.39-1.65-1.55-1.93-.16-.28-.02-.43.12-.57.13-.13.28-.33.42-.49.14-.16.19-.28.28-.47.09-.19.05-.35-.02-.49-.07-.14-.64-1.55-.88-2.12-.23-.56-.47-.48-.64-.49h-.54c-.19 0-.49.07-.75.35-.26.28-.99.97-.99 2.36s1.01 2.74 1.15 2.93c.14.19 1.99 3.04 4.83 4.26.67.29 1.2.46 1.61.59.68.22 1.3.19 1.79.12.55-.08 1.66-.68 1.9-1.34.23-.66.23-1.22.16-1.34-.07-.12-.26-.19-.54-.33z" />
      <path d="M26.71 5.29A14.93 14.93 0 0 0 16.05.88C7.75.88 1 7.63 1 15.93c0 2.65.69 5.24 2 7.52L.88 31.12l7.86-2.06a15.02 15.02 0 0 0 7.31 1.86h.01c8.3 0 15.05-6.75 15.05-15.05 0-4.02-1.56-7.8-4.4-10.58zM16.06 28.38h-.01a12.5 12.5 0 0 1-6.36-1.74l-.46-.27-4.66 1.22 1.24-4.54-.3-.47a12.43 12.43 0 0 1-1.9-6.65c0-6.89 5.61-12.5 12.51-12.5 3.34 0 6.47 1.3 8.83 3.66a12.42 12.42 0 0 1 3.66 8.83c0 6.9-5.61 12.51-12.55 12.51z" />
    </svg>
  </a>
</main>
