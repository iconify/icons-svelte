<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c6pqxybel"/><path class="ws4oy3b7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kayak" {...props}></Icon>
<style>
:global(.c6pqxybel) {
  d: path("M3.5 20.5C8 12 12 8 20.5 3.5C16 12 12 16 3.5 20.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ws4oy3b7b) {
  d: path("M10.25 12a1.75 3.25 0 1 0 3.5 0a1.75 3.25 0 1 0-3.5 0Z");
}

</style>
