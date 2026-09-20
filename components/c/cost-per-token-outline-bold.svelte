<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ry_f-ms3l"/><path class="an7tqs10g"/><path class="i5be34b7d"/><path class="h0r-78wsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cost-per-token-outline-bold" {...props}></Icon>
<style>
:global(.an7tqs10g) {
  d: path("M10 12h3");
}

:global(.h0r-78wsa) {
  d: path("M17 10v4");
}

:global(.i5be34b7d) {
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.ry_f-ms3l) {
  d: path("M2 12a3 3 0 0 1 3 -3 3 3 0 0 1 3 3 3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
