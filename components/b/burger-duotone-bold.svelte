<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="djnsk5v5l"/><path class="pry9-wbkg"/><path class="h0mp_outl"/><path class="z8g2jgblp"/><path class="yvj012pxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:burger-duotone-bold" {...props}></Icon>
<style>
:global(.djnsk5v5l) {
  fill: currentColor;
  d: path("M5 9c0 -4 3 -7 7 -7s7 3 7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h0mp_outl) {
  d: path("M5 9c0 -4 3 -7 7 -7s7 3 7 7Z");
}

:global(.pry9-wbkg) {
  fill: currentColor;
  d: path("M5 15h14v3a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yvj012pxv) {
  d: path("M5 15h14v3a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3Z");
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

</style>
