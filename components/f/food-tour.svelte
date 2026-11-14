<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wnjgeoakk"/><path class="sdh2e4zrl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:food-tour" {...props}></Icon>
<style>
:global(.sdh2e4zrl) {
  d: path("M7 5.5V9a2 2 0 0 0 4 0V5.5m4 13v-13c-1.5 1.5-1.5 5.5 0 7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wnjgeoakk) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM9 5.5v13");
}

</style>
