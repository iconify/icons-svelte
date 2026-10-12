<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="drmrwvbgh"/><path class="uy1khubuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:autopay-sharp" {...props}></Icon>
<style>
:global(.drmrwvbgh) {
  cx: 10px;
  cy: 14.25px;
  r: 6.75px;
}

:global(.uy1khubuk) {
  d: path("m11.81 12.79l-.435-1.08H8.39v1.33c0 1.77 3.56.99 3.56 2.88v1.36H8.77l-.54-1.08M20.5 2.75l-2.75 3.5H21L18.75 9.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
