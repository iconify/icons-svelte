<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ybv62wvzp"/><circle class="wijmr5spd"/><circle class="q25-p6_uv"/><path class="vjw_whbgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:random-forest" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q25-p6_uv) {
  cx: 18.5px;
  cy: 10.5px;
  r: 2.5px;
}

:global(.vjw_whbgg) {
  d: path("M5.5 13v7.75m6.5-12v12M18.5 13v7.75");
}

:global(.wijmr5spd) {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

:global(.ybv62wvzp) {
  cx: 5.5px;
  cy: 10.5px;
  r: 2.5px;
}

</style>
