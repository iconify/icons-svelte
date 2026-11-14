<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gd0oribsf"/><path class="wxo8q1bbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:custody-calendar" {...props}></Icon>
<style>
:global(.gd0oribsf) {
  d: path("M6.5 4h11A3.5 3.5 0 0 1 21 7.5V18a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18V7.5A3.5 3.5 0 0 1 6.5 4M8 2.5v3m8-3v3m-13 3h18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wxo8q1bbv) {
  fill: currentColor;
  d: path("M8 11.5zA1.5 1.5 0 0 1 9.5 13A1.5 1.5 0 0 1 8 14.5A1.5 1.5 0 0 1 6.5 13A1.5 1.5 0 0 1 8 11.5m8 4.25za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
