<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_roqnvgw"/><path class="g3zsjtbwt"/><path class="u0f8zmbjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:canvas-roll" {...props}></Icon>
<style>
:global(.g3zsjtbwt) {
  d: path("M6 3h11.5a2.75 5 0 0 1 0 10H6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u0f8zmbjv) {
  d: path("M20.25 8v12.5H6V13");
}

:global(.v_roqnvgw) {
  d: path("M3.25 8a2.75 5 0 1 0 5.5 0a2.75 5 0 1 0-5.5 0");
}

</style>
