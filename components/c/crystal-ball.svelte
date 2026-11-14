<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1p54ripv"/><path class="yoz2ntbog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crystal-ball" {...props}></Icon>
<style>
:global(.a1p54ripv) {
  d: path("M7.5 16a7.5 7.5 0 1 1 9 0m-9 0l-3 5h15l-3-5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yoz2ntbog) {
  d: path("M8 10a4 4 0 0 1 4-4");
}

</style>
