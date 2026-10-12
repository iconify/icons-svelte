<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z497j5bzr"/><circle class="ugkzx-t0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dome-camera-sharp" {...props}></Icon>
<style>
:global(.ugkzx-t0u) {
  cx: 13px;
  cy: 12.75px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z497j5bzr) {
  d: path("M2.75 5.25h18.5M3 8.25h18a9 9 0 0 1-18 0Z");
}

</style>
