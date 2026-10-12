<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wm0uv6bvb"/><circle class="vf78g51_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:moon-phases-sharp" {...props}></Icon>
<style>
:global(.vf78g51_u) {
  cx: 18.75px;
  cy: 12px;
  r: 2.5px;
}

:global(.wm0uv6bvb) {
  d: path("M13.75 4.58a8 8 0 1 0 0 14.84a8.5 8.5 0 0 1 0-14.84Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
