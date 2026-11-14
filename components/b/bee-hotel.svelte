<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k4ozd9cjr"/><path class="mxqoledjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bee-hotel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k4ozd9cjr) {
  d: path("m5.104 8.477l5.75-4.984a1.75 1.75 0 0 1 2.292 0l5.75 4.984a1.75 1.75 0 0 1 .604 1.322v9.951a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75V9.799a1.75 1.75 0 0 1 .604-1.322");
}

:global(.mxqoledjd) {
  d: path("M10.25 11.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M7 17a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 7 17m6.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
