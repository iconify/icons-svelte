<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="szabki7pt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:compute-node" {...props}></Icon>
<style>
:global(.szabki7pt) {
  d: path("M8.5 8.5h7v7h-7Zm2-1.25V8.5m3-1.25V8.5m-3 7v1.25m3-1.25v1.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wrcg6qhaf) {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>
