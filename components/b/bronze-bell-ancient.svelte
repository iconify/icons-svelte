<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctg3ymv3b"/><path class="jl8fukfcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bronze-bell-ancient" {...props}></Icon>
<style>
:global(.ctg3ymv3b) {
  d: path("M7 18v-6a5 5 0 0 1 10 0v6l2.5 2.5h-15Z");
}

:global(.jl8fukfcs) {
  d: path("M10 7.5v-2a2 2 0 0 1 4 0v2m-7 6h10m-10 3h10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
