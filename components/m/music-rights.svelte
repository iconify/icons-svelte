<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xvrt78hka"/><path class="yh8y5j3yq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:music-rights" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xvrt78hka) {
  d: path("M3.5 16.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m5.5 0V3m0 0c1.5 3 5.5 3.5 5.5 7.5m-.75 7.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.yh8y5j3yq) {
  d: path("M18.75 16.5a1.75 1.75 0 1 0 0 2.5");
}

</style>
