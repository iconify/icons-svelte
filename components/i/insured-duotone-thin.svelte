<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j5hk4ybky"/><path class="jsn86acrn"/><path class="h51gqww2n"/><path class="bm68p9f0y"/><path class="vt0s7oznm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:insured-duotone-thin" {...props}></Icon>
<style>
:global(.bm68p9f0y) {
  d: path("M6.5 10.5v3");
}

:global(.h51gqww2n) {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j5hk4ybky) {
  fill: currentColor;
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jsn86acrn) {
  fill: currentColor;
  d: path("M14 7h8v5.5l-4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vt0s7oznm) {
  d: path("M14 7h8v5.5l-4 4 -4 -4Z");
}

</style>
