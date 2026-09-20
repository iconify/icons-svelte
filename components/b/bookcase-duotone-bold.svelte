<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bazq81bsf"/><path class="d3xn50bni"/><path class="jof7c9fpk"/><path class="m-p3hbclp"/><path class="i00_u5bmc"/><path class="piffzybwc"/><path class="tv8fpliqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bookcase-duotone-bold" {...props}></Icon>
<style>
:global(.bazq81bsf) {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d3xn50bni) {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.i00_u5bmc) {
  d: path("M8 4v5");
}

:global(.jof7c9fpk) {
  d: path("M4 9h16");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.piffzybwc) {
  d: path("M11 4v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tv8fpliqa) {
  d: path("M8 15v6");
}

</style>
