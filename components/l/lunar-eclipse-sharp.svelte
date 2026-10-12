<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="qeablobnc"/><path class="zxxzs1l8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lunar-eclipse-sharp" {...props}></Icon>
<style>
:global(.qeablobnc) {
  cx: 13px;
  cy: 13px;
  r: 8.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zxxzs1l8w) {
  d: path("M4.75 12.81a8.25 8.25 0 0 1 6.57-7.89a10.5 10.5 0 0 1-6.57 7.89Zm0 0a10.5 10.5 0 0 1-1.63.49m8.38-9.8a10.5 10.5 0 0 1-.18 1.42");
}

</style>
