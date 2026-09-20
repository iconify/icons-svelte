<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oupslkbfk"/><path class="s25vf1bvx"/><path class="ggik2wgcv"/><path class="m6r9k7-tj"/><path class="dwlya1t8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:payroll-run-duotone-thin" {...props}></Icon>
<style>
:global(.dwlya1t8x) {
  d: path("m13.5 12 2.5 2.5 -2.5 2.5");
}

:global(.ggik2wgcv) {
  d: path("M9 9V5h6v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m6r9k7-tj) {
  d: path("M8 14.5h8");
}

:global(.oupslkbfk) {
  fill: currentColor;
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s25vf1bvx) {
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
