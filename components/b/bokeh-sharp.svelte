<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="g8ubobbck"/><circle class="pf8xrvdha"/><circle class="y2v2ieaqm"/><circle class="m-b__ibxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bokeh-sharp" {...props}></Icon>
<style>
:global(.g8ubobbck) {
  cx: 8px;
  cy: 8px;
  r: 5.25px;
}

:global(.m-b__ibxs) {
  cx: 6px;
  cy: 18.5px;
  r: 2px;
}

:global(.pf8xrvdha) {
  cx: 16.75px;
  cy: 16.5px;
  r: 4.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y2v2ieaqm) {
  cx: 18.25px;
  cy: 6px;
  r: 2.25px;
}

</style>
