<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="asf-0gpsd"/><path class="yyewitsbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:closed-bookings" {...props}></Icon>
<style>
:global(.asf-0gpsd) {
  d: path("M3.5 4.5h17v17h-17Zm4.5-2v4m8-4v4m-12.5 3h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yyewitsbk) {
  d: path("m8.5 15l2.5 2.5l4.5-5");
}

</style>
