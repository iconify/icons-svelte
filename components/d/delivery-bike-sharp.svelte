<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rslc-9wef"/><circle class="j-97t6czk"/><path class="b_l1l_b8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:delivery-bike-sharp" {...props}></Icon>
<style>
:global(.b_l1l_b8b) {
  d: path("m6 18l3.5-7h5.75m-3.5 7L9.5 11m2.25 7l3.5-7M18 18L14.25 7.25h-2M8 8.75h3m6.75-4.25h3.5v3.25h-3.5z");
}

:global(.j-97t6czk) {
  cx: 18px;
  cy: 18px;
  r: 3.25px;
}

:global(.rslc-9wef) {
  cx: 6px;
  cy: 18px;
  r: 3.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
