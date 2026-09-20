<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1-eezbzd"/><path class="jlgxzd_ny"/><path class="rlk52sj8y"/><path class="oyxdwu0be"/><path class="c4o3x9bhp"/><path class="a97qfmbix"/><path class="f2vh026ub"/><path class="uadefenvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:network-policy-duotone-thin" {...props}></Icon>
<style>
:global(.a97qfmbix) {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.c4o3x9bhp) {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.f2vh026ub) {
  d: path("M10 9h4");
}

:global(.h1-eezbzd) {
  fill: currentColor;
  d: path("M15 3h5v8l-8 8 -8 -8V3h5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlgxzd_ny) {
  fill: currentColor;
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oyxdwu0be) {
  d: path("M15 3h5v8l-8 8 -8 -8V3h5Z");
}

:global(.rlk52sj8y) {
  fill: currentColor;
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uadefenvd) {
  d: path("M7 22h10");
}

</style>
