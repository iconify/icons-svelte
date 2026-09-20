<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j93aodlin"/><path class="dktry7bqc"/><path class="rxwr8htky"/><path class="o_lgmdh9h"/><path class="etv8-wbhu"/><path class="pmuiqo95v"/><path class="l2x-_sd5q"/><path class="bo51iypxr"/><path class="l3ca9u8kt"/><path class="w8vefpfbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:node-selector-duotone-bold" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.etv8-wbhu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j93aodlin) {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l2x-_sd5q) {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l3ca9u8kt) {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.o_lgmdh9h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.rxwr8htky) {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.w8vefpfbs) {
  d: path("m10 5 2 2 2 -2");
}

</style>
