<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cbib95b3k"/><path class="j6e14gbvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pool-pump" {...props}></Icon>
<style>
:global(.cbib95b3k) {
  d: path("M3.5 12a6 1.75 0 0 1 12 0v7.5a6 1.75 0 0 1-12 0Z");
}

:global(.j6e14gbvt) {
  d: path("M5 4h9v6.25H5Zm10.5 11.5H20m0-2v4m-16.5-2a6 1.75 0 0 0 12 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
