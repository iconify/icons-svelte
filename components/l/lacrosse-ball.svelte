<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ruyt_r40r"/><path class="g46q1ac-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lacrosse-ball" {...props}></Icon>
<style>
:global(.g46q1ac-i) {
  d: path("M10 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ruyt_r40r) {
  d: path("M8.5 13L6 6c-.5-2.5 1.5-3.5 4-3.5h4.5c3 0 4.5 2 3.5 4.5l-4.5 6Zm2.5 0l4 8.5");
}

</style>
