<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="gghcu9x9r"/><path class="uzx24gbgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fingerprint-scanner-police" {...props}></Icon>
<style>
:global(.gghcu9x9r) {
  d: path("M8 14.5v-4a4 4 0 0 1 8 0v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o72zbacef) {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

:global(.uzx24gbgo) {
  d: path("M10.75 14.5v-4a1.25 1.25 0 0 1 2.5 0v4M9 18h6");
}

</style>
