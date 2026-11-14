<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m6kkv_bev"/><path class="rnbphpbjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chat-routing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m6kkv_bev) {
  d: path("M2.5 7.5A2.5 2.5 0 0 1 5 5h6a2.5 2.5 0 0 1 2.5 2.5V13a2.5 2.5 0 0 1-2.5 2.5H8.5l-3 3v-3H5A2.5 2.5 0 0 1 2.5 13Zm11 2.5h3l4-4m-4 4l4 4");
}

:global(.rnbphpbjs) {
  d: path("M18 6h2.5v2.5m0 3V14H18");
}

</style>
