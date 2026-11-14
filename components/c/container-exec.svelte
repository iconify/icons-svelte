<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wvgttlb7s"/><path class="d4zy6pbrc"/><path class="y_ieg5bji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:container-exec" {...props}></Icon>
<style>
:global(.d4zy6pbrc) {
  d: path("m6.5 7.25l3 3l-3 3m5 0h2.3M18 15l2.75 1.5v3L18 21l-2.75-1.5v-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wvgttlb7s) {
  d: path("M12.2 18H2.5V3H20v9.9");
}

:global(.y_ieg5bji) {
  d: path("M15.25 16.5L18 18l2.75-1.5M18 18v3");
}

</style>
