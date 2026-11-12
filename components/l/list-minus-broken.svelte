<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qesyv5buv"/><path class="djbi_ub-i"/><path class="k2s9xcb6i"/><path class="spodu6bqp"/><path class="i98cvin-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-minus-broken" {...props}></Icon>
<style>
:global(.djbi_ub-i) {
  d: path("M11 18H3");
}

:global(.i98cvin-m) {
  d: path("M21 10L9.88235 10M5.38235 10H3");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2s9xcb6i) {
  d: path("M21 16.5H14");
}

:global(.qesyv5buv) {
  d: path("M11 14L3 14");
}

:global(.spodu6bqp) {
  d: path("M3 6L14.1176 6M18.6176 6H21");
}

</style>
