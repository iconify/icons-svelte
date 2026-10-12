<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="j27ge1erz"/><circle class="nw8c9yb7d"/><circle class="pvqx9m57v"/><path class="rql36wqjt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:audience-growth-sharp" {...props}></Icon>
<style>
:global(.j27ge1erz) {
  cx: 5.83px;
  cy: 13.5px;
  r: 1.75px;
}

:global(.nw8c9yb7d) {
  cx: 12px;
  cy: 13.5px;
  r: 1.75px;
}

:global(.pvqx9m57v) {
  cx: 18.17px;
  cy: 13.5px;
  r: 1.75px;
}

:global(.rql36wqjt) {
  d: path("M2.75 21.25a3.08 3.08 0 0 1 6.17 0a3.08 3.08 0 0 1 6.17 0a3.08 3.08 0 0 1 6.17 0M5.5 2.75h13v6h-13z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
