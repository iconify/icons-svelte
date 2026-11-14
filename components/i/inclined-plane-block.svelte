<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tcwlcw27i"/><path class="m5pb4jeld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:inclined-plane-block" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m5pb4jeld) {
  d: path("m5.7 8.6l2-1.5a1.75 1.75 0 0 1 2.45.35l1.5 2a1.75 1.75 0 0 1-.35 2.45l-2 1.5a1.75 1.75 0 0 1-2.45-.35l-1.5-2A1.75 1.75 0 0 1 5.7 8.6");
}

:global(.tcwlcw27i) {
  d: path("M4 18.75h15a1.5 1.5 0 0 0 1.5-1.5V8a1.5 1.5 0 0 0-2.4-1.2L3.9 17.45a1 1 0 0 0-.4.8a.5.5 0 0 0 .5.5");
}

</style>
