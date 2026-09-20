<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="whr8-ccry"/><path class="rhm47qbih"/><path class="w5ztjmaaw"/><path class="nmydmacrd"/><path class="t4q7b5q6x"/><path class="x1gscpb4z"/><path class="pmuiqo95v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:campsite-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nmydmacrd) {
  d: path("m12 14 5 -5 5 5Z");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.rhm47qbih) {
  fill: currentColor;
  d: path("m12 14 5 -5 5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t4q7b5q6x) {
  d: path("M7 11v3");
}

:global(.w5ztjmaaw) {
  d: path("m2 14 5 -5 5 5Z");
}

:global(.whr8-ccry) {
  fill: currentColor;
  d: path("m2 14 5 -5 5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x1gscpb4z) {
  d: path("M17 11v3");
}

</style>
