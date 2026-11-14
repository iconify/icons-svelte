<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ddp8knnno"/><path class="jw1uorb3e"/><path class="cg04wdbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:channel-mixer" {...props}></Icon>
<style>
:global(.cg04wdbau) {
  d: path("M10.5 14.75a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0");
}

:global(.ddp8knnno) {
  d: path("M6.75 8.25a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jw1uorb3e) {
  d: path("M3 14.75a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0");
}

</style>
