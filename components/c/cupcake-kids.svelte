<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ud8e23bmd"/><path class="fa8jygytk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cupcake-kids" {...props}></Icon>
<style>
:global(.fa8jygytk) {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ud8e23bmd) {
  d: path("M5 13h14l-1.5 8.5h-11Zm0 0c-1.5 0-1.5-3 1-3c0-2.5 3-3.5 6-3.5s6 1 6 3.5c2.5 0 2.5 3 1 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
