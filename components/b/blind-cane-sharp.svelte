<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dc_3ayb6q"/><path class="oje8oguzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blind-cane-sharp" {...props}></Icon>
<style>
:global(.dc_3ayb6q) {
  cx: 10px;
  cy: 4.5px;
  r: 1.75px;
}

:global(.oje8oguzr) {
  d: path("m10 8l-1 6l2.5 3v4.25M9 14l-2.5 7.25M9.75 9.5l3.5 3.25m0 0l5.75 8.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
