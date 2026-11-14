<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w66khpujm"/><path class="gr06dba8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lab-cloud" {...props}></Icon>
<style>
:global(.gr06dba8o) {
  d: path("M15 6V3h2v4.75M8.75 7.5V10l-2.5 4h7l-2.5-4V7.5m5.5 14h3.5A1.75 1.75 0 0 0 20 18a2.75 2.75 0 0 0-5.25.5a1.5 1.5 0 0 0 1.5 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w66khpujm) {
  d: path("M11.06 19.5H3v-10l8-7l8 7v4.14");
}

</style>
