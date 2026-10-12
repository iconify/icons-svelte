<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6k37htuo"/><rect class="cavpvedfq"/><circle class="r6uvok62f"/><path class="q48h0ehee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ornament-ball" {...props}></Icon>
<style>
:global(.cavpvedfq) {
  width: 4.5px;
  height: 2.5px;
  x: 9.75px;
  y: 4.25px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p6k37htuo) {
  d: path("M11 3.75a1 1 0 0 1 2 0");
}

:global(.q48h0ehee) {
  d: path("m5.75 13.25l2.1 1.5l2.05-1.5l2.1 1.5l2.1-1.5l2.05 1.5l2.1-1.5M8 9.75h8");
}

:global(.r6uvok62f) {
  cx: 12px;
  cy: 14px;
  r: 7.25px;
}

</style>
