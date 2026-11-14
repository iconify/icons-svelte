<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ppt24jbbu"/><path class="bicjjbbko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:robot-vacuum-map" {...props}></Icon>
<style>
:global(.bicjjbbko) {
  d: path("M6 16.5q.5-6 6-5.5m3-1.75h.01M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.ppt24jbbu) {
  d: path("M11.868 19.456L9 18.5l-6 2v-15l6-2l6 2l6-2v8.926");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
