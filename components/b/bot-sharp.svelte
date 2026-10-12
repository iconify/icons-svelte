<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kp14pq1-j"/><path class="r4phunq2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bot-sharp" {...props}></Icon>
<style>
:global(.kp14pq1-j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.5h8.5v7h-8.5zM5 20.25h15v-1c0-3.2-3.6-5.25-8-5.25s-8 2.05-8 5.25v1zM12 4.5V2.75");
}

:global(.r4phunq2g) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 8h.01m3.49 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
