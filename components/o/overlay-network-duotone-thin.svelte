<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vnyqt3_it"/><path class="au1c03bly"/><path class="vefr08bem"/><path class="kllnjy40b"/><path class="j1f41eokg"/><path class="r7bmdibrf"/><path class="pmuiqo95v"/><path class="uxcq0c75d"/><path class="o5h857ycu"/><path class="vq8t-6zzl"/><path class="it83nbbll"/><path class="dxdpz6gbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overlay-network-duotone-thin" {...props}></Icon>
<style>
:global(.au1c03bly) {
  fill: currentColor;
  d: path("M17 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dxdpz6gbz) {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it83nbbll) {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.j1f41eokg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kllnjy40b) {
  fill: currentColor;
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o5h857ycu) {
  d: path("M17 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.r7bmdibrf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 12 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uxcq0c75d) {
  d: path("M5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vefr08bem) {
  fill: currentColor;
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vnyqt3_it) {
  fill: currentColor;
  d: path("M5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vq8t-6zzl) {
  d: path("m6 12 6 -6 6 6");
}

</style>
