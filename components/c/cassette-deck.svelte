<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="mx94nrbna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cassette-deck" {...props}></Icon>
<style>
:global(.mx94nrbna) {
  d: path("M6.5 7.5h11a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Zm2.5 3h.01m5.99 0h.01M7 16.5h10");
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
