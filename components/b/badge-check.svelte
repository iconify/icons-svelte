<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jl4903ezj"/><path class="a6ox1ojiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:badge-check" {...props}></Icon>
<style>
:global(.a6ox1ojiz) {
  d: path("m9.5 9.5l1.75 1.75l3.25-3.5M8.5 15l-1.25 6.25L12 19l4.75 2.25L15.5 15");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jl4903ezj) {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

</style>
