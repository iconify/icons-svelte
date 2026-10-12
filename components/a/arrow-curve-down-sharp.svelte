<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="an8in5bao"/><path class="paivv5b1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-curve-down-sharp" {...props}></Icon>
<style>
:global(.an8in5bao) {
  d: path("M3.75 4.75c8 0 13.25 4.75 13.25 14.5");
}

:global(.paivv5b1d) {
  d: path("m13 15.25l4 4l4-4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
