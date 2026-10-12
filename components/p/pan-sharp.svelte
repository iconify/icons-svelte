<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="nj5ucobzf"/><path class="dvof1ybfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pan-sharp" {...props}></Icon>
<style>
:global(.dvof1ybfg) {
  d: path("M9.75 10a4.25 4.25 0 1 1 0 8.5a4.25 4.25 0 1 1 0-8.5Zm5-.75L16.5 7.5m1.13.63l3-3l.794-.959l-1.76-1.76l-.794.959l-3 3l-.794.959l1.76 1.76z");
}

:global(.nj5ucobzf) {
  cx: 9.75px;
  cy: 14.25px;
  r: 7px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
