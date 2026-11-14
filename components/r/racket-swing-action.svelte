<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k4mwhczgm"/><path class="tovuih4je"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:racket-swing-action" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k4mwhczgm) {
  d: path("M7.75 9a4.5 6.25 0 1 0 9 0a4.5 6.25 0 1 0-9 0m2.129 5.475l-6.188 6.187");
}

:global(.tovuih4je) {
  d: path("M6.25 10.25a8 8 0 0 1 4-7");
}

</style>
