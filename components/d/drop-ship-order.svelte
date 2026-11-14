<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rylwk1z8m"/><path class="mxfa78qmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:drop-ship-order" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mxfa78qmp) {
  d: path("m12.513 14.987l3-3a1.75 1.75 0 0 1 2.474 0l3 3a1.75 1.75 0 0 1 .513 1.238v3.525a1.75 1.75 0 0 1-1.75 1.75h-6A1.75 1.75 0 0 1 12 19.75v-3.525a1.75 1.75 0 0 1 .513-1.238");
}

:global(.rylwk1z8m) {
  d: path("M2.5 2.5h6v6h-6Zm6 6l5.25 5.25m-3 0h3v-3");
}

</style>
