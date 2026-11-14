<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="iad5g1cgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:closed-captions-badge" {...props}></Icon>
<style>
:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.iad5g1cgi) {
  d: path("M10.25 10a2.75 2.75 0 1 0 0 4m7.5-4a2.75 2.75 0 1 0 0 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
