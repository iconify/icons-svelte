<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o05bagdfy"/><path class="tpkrj5bei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coach-whistle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o05bagdfy) {
  d: path("M3 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.tpkrj5bei) {
  d: path("m13 11.5l8-3V12l-7 2.25M7 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M8.5 3.5V6");
}

</style>
