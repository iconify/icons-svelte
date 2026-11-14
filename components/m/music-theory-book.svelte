<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0twtl96g"/><path class="yff-74b6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:music-theory-book" {...props}></Icon>
<style>
:global(.u0twtl96g) {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yff-74b6o) {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5m-7.5-3V5q3.25.75 1.5 3.25l-4 3a2.5 2.5 0 0 0 5 0a2.5 2.5 0 0 0-2.5-2.5");
}

</style>
