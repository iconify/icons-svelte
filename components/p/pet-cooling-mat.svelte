<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="j-r33lewh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pet-cooling-mat" {...props}></Icon>
<style>
:global(.j-r33lewh) {
  d: path("M6 8.75q3-2.25 6 0t6 0M6 12q3-2.25 6 0t6 0M6 15.25q3-2.25 6 0t6 0");
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
