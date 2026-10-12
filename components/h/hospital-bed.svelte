<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gplilobog"/><circle class="akzn_2afg"/><path class="tdx_tmbvg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hospital-bed" {...props}></Icon>
<style>
:global(.akzn_2afg) {
  cx: 7.25px;
  cy: 11.5px;
  r: 2px;
}

:global(.gplilobog) {
  d: path("M2.75 5.5v14.75m0-4.25h18v4.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tdx_tmbvg) {
  d: path("M11.75 16v-4.25a1.5 1.5 0 0 1 1.5-1.5h6a1.5 1.5 0 0 1 1.5 1.5V16M16 3.75v4.5M13.75 6h4.5");
}

</style>
