<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bp7wkccig"/><path class="bix35ybqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:robot-vacuum-brush" {...props}></Icon>
<style>
:global(.bix35ybqr) {
  d: path("M3 8v3a9 3.5 0 0 0 18 0V8M5 17.25h14v3H5Z");
}

:global(.bp7wkccig) {
  d: path("M3 8a9 3.5 0 1 0 18 0A9 3.5 0 1 0 3 8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
