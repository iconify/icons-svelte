<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xeah6_3zx"/><path class="k6tdchb3v"/><circle class="hxly0r3mq"/><circle class="prxayub-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dish-soap-sharp" {...props}></Icon>
<style>
:global(.hxly0r3mq) {
  cx: 18.75px;
  cy: 4.75px;
  r: 1.75px;
}

:global(.k6tdchb3v) {
  d: path("m12 12.25l1.5 1.725v.925a1.5 1.5 0 0 1-3 0v-.925z");
}

:global(.prxayub-e) {
  cx: 5.5px;
  cy: 4.25px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xeah6_3zx) {
  d: path("M10.25 4.25h3.5v4h-3.5zm-2 4h9.5v13H6.25v-13z");
}

</style>
