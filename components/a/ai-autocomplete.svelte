<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e_gn0vonc"/><path class="saexkybjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ai-autocomplete" {...props}></Icon>
<style>
:global(.e_gn0vonc) {
  width: 18.5px;
  height: 9.5px;
  x: 2.75px;
  y: 10px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.saexkybjd) {
  d: path("M6 14.75h4m1.75-2.5v5m2.25-2.5h1m1.75 0h1m1-12Q19.02 4.73 21 5q-1.98.27-2.25 2.25Q18.48 5.27 16.5 5q1.98-.27 2.25-2.25");
}

</style>
