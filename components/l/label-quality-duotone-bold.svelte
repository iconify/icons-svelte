<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fbde_z08y"/><path class="r8hnofl7s"/><path class="pb8u2_oec"/><path class="w3hyiobto"/><path class="hgb-t7boy"/><path class="zf4ugsben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:label-quality-duotone-bold" {...props}></Icon>
<style>
:global(.fbde_z08y) {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hgb-t7boy) {
  d: path("M6 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pb8u2_oec) {
  fill: currentColor;
  d: path("m12 11 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r8hnofl7s) {
  fill: currentColor;
  d: path("M6 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.w3hyiobto) {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

:global(.zf4ugsben) {
  d: path("m12 11 3 3 -3 3 -3 -3Z");
}

</style>
