<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cp0gl0c0y"/><path class="lh5e97fgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:decor-bowl" {...props}></Icon>
<style>
:global(.cp0gl0c0y) {
  d: path("M2.5 7h19a9.5 6.5 0 0 1-19 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lh5e97fgk) {
  d: path("m9.5 13.25l-1 4.25h7l-1-4.25");
}

</style>
