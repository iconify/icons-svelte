<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oi6zdub0w"/><path class="e0x1-1bno"/><path class="wh7wfbbvx"/><path class="ax1yrr41w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:art-print" {...props}></Icon>
<style>
:global(.ax1yrr41w) {
  d: path("m7.5 18.75l2.75-4.25L13 18.75");
}

:global(.e0x1-1bno) {
  d: path("M2.5 5.5H18v16H2.5Z");
}

:global(.oi6zdub0w) {
  d: path("M10 5.5v-3h11.5V14H18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wh7wfbbvx) {
  d: path("M5.25 8.25h10v10.5h-10Z");
}

</style>
