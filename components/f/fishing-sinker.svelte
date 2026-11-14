<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cy-bn3b7f"/><path class="vbwf96hud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fishing-sinker" {...props}></Icon>
<style>
:global(.cy-bn3b7f) {
  d: path("M12 8.75c2.5 2.25 5 4.75 5 7.75a5 5 0 0 1-10 0c0-3 2.5-5.5 5-7.75Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vbwf96hud) {
  d: path("M10.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 2.5v2.75");
}

</style>
