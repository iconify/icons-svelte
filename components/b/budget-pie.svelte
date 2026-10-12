<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2hd4ubib"/><path class="s7y2fi7md"/><circle class="px3vvqhil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:budget-pie" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2hd4ubib) {
  d: path("M8.75 5.75a6 6 0 1 0 6 6h-6Z");
}

:global(.px3vvqhil) {
  cx: 18.75px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.s7y2fi7md) {
  d: path("M11.75 2.75a6 6 0 0 1 6 6h-6Z");
}

</style>
