<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="muokhubdq"/><circle class="u2y4_zbrn"/><circle class="k__z_1b2n"/><path class="ps32ppjfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ham" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k__z_1b2n) {
  cx: 6.75px;
  cy: 4.5px;
  r: 1.5px;
}

:global(.muokhubdq) {
  d: path("M9.75 7.75Q11.75 9 14 9.1A6 6 0 1 1 9.1 14Q9 11.75 7.75 9.75Zm-1 1L6 6");
}

:global(.ps32ppjfb) {
  d: path("M17.6 13.5a3 3 0 0 1-4.1 4.1");
}

:global(.u2y4_zbrn) {
  cx: 4.5px;
  cy: 6.75px;
  r: 1.5px;
}

</style>
