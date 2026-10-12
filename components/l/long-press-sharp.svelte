<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m2to5dbhq"/><path class="w0y_71b6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:long-press-sharp" {...props}></Icon>
<style>
:global(.m2to5dbhq) {
  d: path("M9.75 16V9.25h2.5V14h4.25v7.25H7.75V16h1Zm2.5-1.5v2.25");
}

:global(.w0y_71b6m) {
  d: path("M6.24 13.25A5.5 5.5 0 1 1 16.5 10.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
