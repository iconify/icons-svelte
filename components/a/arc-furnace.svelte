<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zhyy9gbtz"/><path class="aiaz2ro_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arc-furnace" {...props}></Icon>
<style>
:global(.aiaz2ro_g) {
  d: path("m12.75 14l-1.5 2.25h1.5l-1.5 2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zhyy9gbtz) {
  d: path("M3 11h18c0 6-4 10-9 10s-9-4-9-10Zm5.5-8.5v12m7-12v12");
}

</style>
