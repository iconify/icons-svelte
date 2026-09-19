<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o312kkdpi"/><path class="sc02cqbvc"/><path class="f3hbwibhd"/><path class="b2rx1obdk"/><circle class="sqxu05bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:feit-electric" {...props}></Icon>
<style>
:global(.b2rx1obdk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.782 25.998a6.744 6.744 0 0 1 10.149-.074m-8.075 2.074a3.828 3.828 0 0 1 6 .074");
}

:global(.f3hbwibhd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.744 23.775c7.687-7.074 14.225 0 14.225 0");
}

:global(.o312kkdpi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.48 7.33l.182 28.301c.074 6.24.046 6.238 4.782 6.31l15.188.045c4.817.002 4.815.003 4.889-5.912V26.22");
}

:global(.sc02cqbvc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.664 22.368L20.765 7.683c2.753-2.265 3.668-2.279 6.7.293l14.87 14.317");
}

:global(.sqxu05bpj) {
  cx: 24px;
  cy: 30.779px;
  r: 1.274px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
