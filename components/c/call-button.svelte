<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tyvd2kp8c"/><path class="mgveaccwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:call-button" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mgveaccwg) {
  d: path("M8 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0m2 7h4");
}

:global(.tyvd2kp8c) {
  d: path("M10.25 2.5h3.5A5.25 5.25 0 0 1 19 7.75v8.5a5.25 5.25 0 0 1-5.25 5.25h-3.5A5.25 5.25 0 0 1 5 16.25v-8.5a5.25 5.25 0 0 1 5.25-5.25");
}

</style>
