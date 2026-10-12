<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mm1i4--nu"/><circle class="fd2ud0b_q"/><circle class="jdahq6biz"/><path class="cd596su5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:loading-dock-sharp" {...props}></Icon>
<style>
:global(.cd596su5p) {
  d: path("M11.75 21.25h9.5");
}

:global(.fd2ud0b_q) {
  cx: 17.25px;
  cy: 19px;
  r: 1.25px;
}

:global(.jdahq6biz) {
  cx: 20px;
  cy: 19px;
  r: 1.25px;
}

:global(.mm1i4--nu) {
  d: path("M2.75 12.75h9v8.5h-9zm10 .5L15 15m1-10h5.25v11.5H16z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
