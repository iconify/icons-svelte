<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="gxrppfboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:race-dashboard" {...props}></Icon>
<style>
:global(.gxrppfboa) {
  d: path("M7 13.5a5 5 0 0 1 10 0m-5 0l3-3m-7.5 5.75h9");
}

:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
