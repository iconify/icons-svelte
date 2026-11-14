<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="no92k1blf"/><path class="h56c3lwoj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:muscle-group" {...props}></Icon>
<style>
:global(.h56c3lwoj) {
  d: path("M13 16.5q2.5-2 5-.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.no92k1blf) {
  d: path("M21 21.5H6.5c-3 0-3.5-2.5-2.5-5L7 6c.5-2 2-3 4-3h2.5c1.5 0 2 1.5 1 2.5l-3 2l-2 5.5c2.5-2.5 7.5-3 9.5-.5c1.5 1.5 2 3 2 4.5Z");
}

</style>
