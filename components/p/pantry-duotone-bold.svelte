<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y1nfwg_iv"/><path class="d5b4fcc2f"/><path class="omdp355hx"/><path class="s2n9l4i0j"/><path class="k187sabpz"/><path class="z9ittvbis"/><path class="mia87q3wc"/><path class="a1mgubcgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pantry-duotone-bold" {...props}></Icon>
<style>
:global(.a1mgubcgh) {
  d: path("M13 19v-5h4v5");
}

:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.mia87q3wc) {
  d: path("M5 11V6h4v5");
}

:global(.omdp355hx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11V6h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s2n9l4i0j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 19v-5h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y1nfwg_iv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
