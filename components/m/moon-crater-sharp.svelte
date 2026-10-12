<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m4l-9ybuj"/><circle class="cz52nob5z"/><circle class="wtqeeyb2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:moon-crater-sharp" {...props}></Icon>
<style>
:global(.cz52nob5z) {
  cx: 9px;
  cy: 9.5px;
  r: 2px;
}

:global(.m4l-9ybuj) {
  cx: 12px;
  cy: 12px;
  r: 9px;
}

:global(.wtqeeyb2r) {
  cx: 14.5px;
  cy: 15px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
