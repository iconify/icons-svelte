<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7ui8x8td"/><circle class="lzanorbmf"/><circle class="dn0bjhepg"/><circle class="bn_m5u55m"/><path class="kkvfp_m1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:face-mind-blown" {...props}></Icon>
<style>
:global(.bn_m5u55m) {
  cx: 12px;
  cy: 17.75px;
  r: 1px;
}

:global(.dn0bjhepg) {
  cx: 15px;
  cy: 14.75px;
  r: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k7ui8x8td) {
  d: path("M5 11.75h14a1 1 0 0 1 1 1v.5a8 8 0 0 1-16 0v-.5a1 1 0 0 1 1-1");
}

:global(.kkvfp_m1y) {
  d: path("M7.25 9.25a1.9 1.9 0 0 1-.4-3.75a2.75 2.75 0 0 1 5.15-1a2.75 2.75 0 0 1 5.15 1a1.9 1.9 0 0 1-.4 3.75Z");
}

:global(.lzanorbmf) {
  cx: 9px;
  cy: 14.75px;
  r: 1px;
}

</style>
