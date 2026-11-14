<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jcu3vxbbi"/><path class="c06clhbbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camera-rolling" {...props}></Icon>
<style>
:global(.c06clhbbg) {
  d: path("M5 6.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm7 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.jcu3vxbbi) {
  d: path("M2.5 10.5h13V20h-13Zm13 2.5l6-2.5v9l-6-2.5Zm-13-6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
