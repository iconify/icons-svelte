<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxsxh5xhc"/><path class="zbi238bfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pc-tower-power" {...props}></Icon>
<style>
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

:global(.zbi238bfj) {
  d: path("M14.089 8.01a3.25 3.25 0 1 1-4.178 0M12 6.25v4");
}

</style>
