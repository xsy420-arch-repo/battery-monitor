pkgname=battery-monitor
pkgver=0.1
pkgrel=1
groups=(xsy420)
arch=(x86_64)
url="https://github.com/xsy420/battery-monitor"
depends=(zenity)
makedepends=(gcc make)
source=("$url/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('0960368cf4153b79fb2c221395079ee915f92c4cc4b81b0c38263bf1d8fc6841')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  make DESTDIR="$pkgdir" install
}

