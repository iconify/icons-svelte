<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh2g22btx"/><path class="ha8apkuln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:priority-sharp" {...props}></Icon>
<style>
:global(.bh2g22btx) {
  d: path("M5.25 9.5L12 2.75l6.75 6.75");
}

:global(.ha8apkuln) {
  d: path("M5.25 14.75L12 8l6.75 6.75M5.25 20L12 13.25L18.75 20");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
