<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="zsqnb834t"/><circle class="a24yqwbfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magazine-sharp" {...props}></Icon>
<style>
:global(.a24yqwbfv) {
  cx: 12px;
  cy: 14.75px;
  r: 3.25px;
}

:global(.ohxdrbbbi) {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zsqnb834t) {
  d: path("M6.75 5.75h10.5v3H6.75z");
}

</style>
