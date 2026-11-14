<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jpcmuhj8m"/><path class="bjxeiwbbv"/><path class="rtaomjblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:people-hugging" {...props}></Icon>
<style>
:global(.bjxeiwbbv) {
  d: path("M5.75 15C9 15 12 17 14 19.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jpcmuhj8m) {
  d: path("M4.5 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m9 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-11 15v-5c0-2.5 2-4.25 5-4.25h9c3 0 5 1.75 5 4.25v5");
}

:global(.rtaomjblp) {
  d: path("M18.25 15C15 15 12 17 10 19.5");
}

</style>
