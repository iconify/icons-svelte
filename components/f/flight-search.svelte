<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtwb_pbpq"/><path class="nzq9s7bqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flight-search" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nzq9s7bqa) {
  d: path("M15.25 17.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

:global(.rtwb_pbpq) {
  d: path("M13.532 20.584L11 20l-3.25.75v-1.5L9.5 17.5V13l-7 2v-1.75L9.5 9V5c0-1.5.5-2.5 1.5-2.5s1.5 1 1.5 2.5v4l5.839 3.545m-3.927 1.001L12.5 13v4.411");
}

</style>
