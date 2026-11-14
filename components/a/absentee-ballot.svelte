<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mvuvuiqwg"/><path class="h9d5l8btt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:absentee-ballot" {...props}></Icon>
<style>
:global(.h9d5l8btt) {
  d: path("m7 3l5 3.5L17 3");
}

:global(.mvuvuiqwg) {
  d: path("M8 12.5H5.5a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-5a2 2 0 0 0-2-2H16m-9-10h10v7H7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
