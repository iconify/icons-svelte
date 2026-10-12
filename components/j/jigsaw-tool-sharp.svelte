<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ps3h4q3zr"/><path class="rj1lvwbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:jigsaw-tool-sharp" {...props}></Icon>
<style>
:global(.ps3h4q3zr) {
  d: path("M5.5 5h14.75v9H3.75V5z");
}

:global(.rj1lvwbse) {
  d: path("M8.25 8H17v2.5H7V8zM6.5 14v3.25m-2.75 0H13M16.25 14v7.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
