<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc0pq4b_o"/><path class="coabtnkvx"/><path class="jbk-w-tox"/><path class="rfy_enbzb"/><path class="g6sdhib4i"/><path class="vslz5yb3q"/><path class="xhm9ckc2y"/><path class="gl0vd86ea"/><path class="h26bvabki"/><path class="tmc4aacim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dumbbell-duotone-thin" {...props}></Icon>
<style>
:global(.cc0pq4b_o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.coabtnkvx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g6sdhib4i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gl0vd86ea) {
  d: path("M18 7v10");
}

:global(.h26bvabki) {
  d: path("M3 9v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jbk-w-tox) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rfy_enbzb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tmc4aacim) {
  d: path("M21 9v6");
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.xhm9ckc2y) {
  d: path("M6 7v10");
}

</style>
