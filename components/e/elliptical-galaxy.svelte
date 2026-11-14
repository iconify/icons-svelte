<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qnmnr3itf"/><path class="mmxhfb3ym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:elliptical-galaxy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mmxhfb3ym) {
  d: path("M5.5 12a6.5 4.25 0 1 0 13 0a6.5 4.25 0 1 0-13 0m6.5 0h.01");
}

:global(.qnmnr3itf) {
  d: path("M2.25 12a9.75 7 0 1 0 19.5 0a9.75 7 0 1 0-19.5 0");
}

</style>
