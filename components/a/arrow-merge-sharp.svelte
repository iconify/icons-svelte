<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mucl2eclq"/><path class="enfkylbcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-merge-sharp" {...props}></Icon>
<style>
:global(.enfkylbcb) {
  d: path("M8.5 7.5L12 4l3.5 3.5");
}

:global(.mucl2eclq) {
  d: path("M5.25 20.25L12 13.5m6.75 6.75L12 13.5v-9");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
