<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gze7vobpe"/><path class="erbzj5b3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:magazine-user" {...props}></Icon>
<style>
:global(.erbzj5b3s) {
  d: path("M9.75 11a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM7.5 18.75C8 16.75 9.75 16 12 16s4 .75 4.5 2.75");
}

:global(.gze7vobpe) {
  d: path("M4.5 2.5h15v19h-15Zm3 3.25h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
