<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s50ix5yvk"/><path class="h_vgq7qci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cricket-sweater" {...props}></Icon>
<style>
:global(.h_vgq7qci) {
  d: path("M8.75 6.75L12 11.5l3.25-4.75M6.5 18h11");
}

:global(.s50ix5yvk) {
  d: path("M8.5 3L3 5.5l.5 6h3V21h11v-9.5h3l.5-6L15.5 3L12 8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
