<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tyvd2kp8c"/><path class="qg8c2gbki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:phone-camera-module" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qg8c2gbki) {
  d: path("M8.25 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m0 6.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M14.5 7.5h.01");
}

:global(.tyvd2kp8c) {
  d: path("M10.25 2.5h3.5A5.25 5.25 0 0 1 19 7.75v8.5a5.25 5.25 0 0 1-5.25 5.25h-3.5A5.25 5.25 0 0 1 5 16.25v-8.5a5.25 5.25 0 0 1 5.25-5.25");
}

</style>
