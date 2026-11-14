<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-iumubfd"/><path class="yv7o50bzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:racecourse" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r-iumubfd) {
  d: path("M4 10c2-1.5 6-1 9-1l3-3.5L17 4l1 1.5l3 3l-1 1.5l-2.5-1l-2 3c-.5 2-2.5 2.5-4.5 2.5H7.5C5.5 14.5 4 13 4 10");
}

:global(.yv7o50bzf) {
  d: path("m14.5 13.75l4 2.25l1.5-1.5m-13.5 0l-3 2.5l-1 3M4.25 9.75C3 9.5 2.5 10.5 2.5 12.5m10 2l1.5 3l-1.5 2");
}

</style>
