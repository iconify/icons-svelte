<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uucuneb6g"/><path class="qpewt2h3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mercury-barometer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qpewt2h3l) {
  d: path("M8 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M13.75 6.5h2.5m-2.5 3.5h1.75m-1.75 3.5h2.5");
}

:global(.uucuneb6g) {
  d: path("M8.5 2.5h7A3.5 3.5 0 0 1 19 6v12a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 18V6a3.5 3.5 0 0 1 3.5-3.5m1.5 3v9.25");
}

</style>
