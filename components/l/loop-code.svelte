<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bwk3snb_t"/><path class="jl12g6iub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:loop-code" {...props}></Icon>
<style>
:global(.bwk3snb_t) {
  d: path("M11.5 4a8 8 0 1 0 8 8");
}

:global(.jl12g6iub) {
  d: path("m17.5 14l2-2l2 2m-12-4.5L7 12l2.5 2.5m4-5L16 12l-2.5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
