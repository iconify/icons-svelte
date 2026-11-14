<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck6lwowvk"/><path class="pt0olsbst"/><path class="s5m-ccupb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-running-track" {...props}></Icon>
<style>
:global(.ck6lwowvk) {
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pt0olsbst) {
  d: path("M10.25 7.5h3.5a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5h-3.5a3.5 3.5 0 0 1-3.5-3.5a3.5 3.5 0 0 1 3.5-3.5");
}

:global(.s5m-ccupb) {
  d: path("M10.25 10.25h3.5a.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75h-3.5A.75.75 0 0 1 9.5 11a.75.75 0 0 1 .75-.75");
}

</style>
