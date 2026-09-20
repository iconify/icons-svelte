<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dth1_3b7x"/><path class="e04igbcxt"/><path class="lz5q8mg1w"/><path class="t2m3fqb7m"/><path class="iu91ib-mt"/><path class="p-3tqnbzb"/><path class="o7w846b2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fertiliser-duotone-bold" {...props}></Icon>
<style>
:global(.dth1_3b7x) {
  fill: currentColor;
  d: path("M6 21V8h12v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e04igbcxt) {
  fill: currentColor;
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iu91ib-mt) {
  d: path("m6 8 3 -3h6l3 3");
}

:global(.lz5q8mg1w) {
  fill: currentColor;
  d: path("M13 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o7w846b2d) {
  d: path("M13 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p-3tqnbzb) {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t2m3fqb7m) {
  d: path("M6 21V8h12v13Z");
}

</style>
