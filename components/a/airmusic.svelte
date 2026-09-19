<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uyc-pnb0e"/><path class="l5cyx4cex"/><path class="c3qlj2v_l"/><circle class="i2xckebcd"/><circle class="hb1cm69fg"/><circle class="iop3htbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:airmusic" {...props}></Icon>
<style>
:global(.c3qlj2v_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.382 14.649v-2.711a1.03 1.03 0 0 0-1.027-1.027h-10.71a1.03 1.03 0 0 0-1.026 1.027v2.71m-.001 5.99v8.17a1.03 1.03 0 0 0 1.027 1.027h10.71a1.03 1.03 0 0 0 1.026-1.027v-8.17");
}

:global(.hb1cm69fg) {
  cx: 24px;
  cy: 23.222px;
  r: 2.718px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i2xckebcd) {
  cx: 24px;
  cy: 14.261px;
  r: 2.023px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.iop3htbce) {
  cx: 24px;
  cy: 23.222px;
  r: 5.058px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.l5cyx4cex) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.618 20.638v-5.99c-4.232 1.077-7.006 3.277-10.521 5.99m33.806 0c-3.515-2.713-6.29-4.913-10.521-5.99v5.99");
}

:global(.uyc-pnb0e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6.322c-8.393 0-14.613 3.387-19.628 7.257a2.265 2.265 0 0 0-.369 3.211L24 41.678L43.997 16.79a2.265 2.265 0 0 0-.369-3.21C38.613 9.708 32.393 6.321 24 6.321");
}

</style>
