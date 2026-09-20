<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xbwcutbts"/><path class="qh3x50ajr"/><path class="j8133bcoj"/><path class="z6y0gfbug"/><path class="a-v3knb-a"/><path class="qgw5bw59f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cash-register-duotone-regular" {...props}></Icon>
<style>
:global(.a-v3knb-a) {
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.j8133bcoj) {
  fill: currentColor;
  d: path("M10 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qgw5bw59f) {
  d: path("M10 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qh3x50ajr) {
  fill: currentColor;
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xbwcutbts) {
  fill: currentColor;
  d: path("M7 4.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2V7a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z6y0gfbug) {
  d: path("M7 4.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2V7a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
