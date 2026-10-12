<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="nj5qkke2z"/><path class="b6g-vuagr"/><circle class="n5rez8zhl"/><path class="ffm-t-bdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:diplomat-sharp" {...props}></Icon>
<style>
:global(.b6g-vuagr) {
  d: path("M2.75 21.25a5.5 6.5 0 0 1 11 0Z");
}

:global(.ffm-t-bdz) {
  d: path("M13.75 7.5h7.5M17.5 3.75L16.15 7.5l1.35 3.75");
}

:global(.n5rez8zhl) {
  cx: 17.5px;
  cy: 7.5px;
  r: 3.75px;
}

:global(.nj5qkke2z) {
  cx: 8.25px;
  cy: 8.25px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
