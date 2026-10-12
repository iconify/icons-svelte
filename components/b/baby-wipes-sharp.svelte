<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hwvgplb-u"/><path class="y0x4d4bgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:baby-wipes-sharp" {...props}></Icon>
<style>
:global(.hwvgplb-u) {
  d: path("M3.75 8.25h16.5v11H3.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0x4d4bgx) {
  d: path("M9.5 11.5C9.5 9 10.75 6.75 12 5c1.25 1.75 2.5 4 2.5 6.5Zm-1 3.25h7");
}

</style>
