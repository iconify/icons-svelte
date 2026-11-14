<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-6rcyi-h"/><path class="i2qq77fsg"/><path class="ox9v0_z-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cable-drum" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-6rcyi-h) {
  d: path("M2.5 11.5a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0M11 20h10.5");
}

:global(.i2qq77fsg) {
  d: path("M8.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.ox9v0_z-p) {
  d: path("M11 6a5.5 5.5 0 1 1-5.5 5.5");
}

</style>
