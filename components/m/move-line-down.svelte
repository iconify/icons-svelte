<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1iz5acmw"/><path class="anzexhb4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:move-line-down" {...props}></Icon>
<style>
:global(.anzexhb4y) {
  d: path("M15.5 16.5L18 19l2.5-2.5");
}

:global(.b1iz5acmw) {
  d: path("M2.5 5h19m-19 14H13M2.5 12h13a2.5 2.5 0 0 1 2.5 2.5V19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
