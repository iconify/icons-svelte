<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="ir4a-mb6j"/><path class="z0-xjdbdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:emissions-down-chart" {...props}></Icon>
<style>
:global(.ir4a-mb6j) {
  d: path("m7 7l3.5 4L13 9l5 5");
}

:global(.j_q_y1bdx) {
  d: path("M3.5 3.5v17h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z0-xjdbdk) {
  d: path("M15 14h3v-3");
}

</style>
