<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mt3ekc3pv"/><path class="dsfrykczg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:last-will-edit" {...props}></Icon>
<style>
:global(.dsfrykczg) {
  d: path("m11.5 17.5l-1 4l4-1");
}

:global(.mt3ekc3pv) {
  d: path("M8.1 19.5H3v-17h13v6.6M6 7h7m-7 4h5m.5 6.5l7-7l3 3l-7 7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
