<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rv7nk5rxi"/><path class="fpqdrwbwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-smart-home" {...props}></Icon>
<style>
:global(.fpqdrwbwc) {
  d: path("M7.327 13.264a3.75 3.75 0 0 1 3.409 3.409M7.632 9.778a7.25 7.25 0 0 1 6.59 6.59");
}

:global(.rv7nk5rxi) {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17ZM7 17h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
