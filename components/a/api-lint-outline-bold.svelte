<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p367mshbv"/><path class="rseiusb3q"/><path class="rxfxjn7zd"/><path class="pa2oc9mpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:api-lint-outline-bold" {...props}></Icon>
<style>
:global(.p367mshbv) {
  d: path("M5.5 10a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

:global(.pa2oc9mpz) {
  d: path("M9.5 11h5");
}

:global(.rseiusb3q) {
  d: path("M16.5 14.5 21 19");
}

:global(.rxfxjn7zd) {
  d: path("M9.5 8h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
