<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qfc520-0g"/><path class="dula946mz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gimbal-stabilizer" {...props}></Icon>
<style>
:global(.dula946mz) {
  d: path("M5 2.5h10V9H5Zm5 3.25h.01");
}

:global(.qfc520-0g) {
  d: path("M9.5 13h5v8.5h-5Zm2.5 0v-1.5h6V5.75h-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
