<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u_fjlxd9t"/><circle class="xipv-o4kn"/><circle class="c-m5iogoj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ratio-sharp" {...props}></Icon>
<style>
:global(.c-m5iogoj) {
  cx: 12px;
  cy: 15.5px;
  r: 1.75px;
}

:global(.u_fjlxd9t) {
  d: path("M5 8v8m14-8v8");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xipv-o4kn) {
  cx: 12px;
  cy: 8.5px;
  r: 1.75px;
}

</style>
