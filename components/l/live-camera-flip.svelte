<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxsxh5xhc"/><path class="d7rcthb9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:live-camera-flip" {...props}></Icon>
<style>
:global(.d7rcthb9d) {
  d: path("M9.185 10.375a3.25 3.25 0 0 1 5.63 0M13.75 9l1.25.75l.75-1.25m-.935 5.125a3.25 3.25 0 0 1-5.63 0M10.25 15L9 14.25l-.75 1.25");
}

:global(.dxsxh5xhc) {
  d: path("M6 2.5h12v19H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
