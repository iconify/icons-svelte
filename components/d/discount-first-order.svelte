<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhe62-b5n"/><path class="catadcc6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:discount-first-order" {...props}></Icon>
<style>
:global(.catadcc6k) {
  d: path("m10 13.5l2.5-2V18M10 18h4.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lhe62-b5n) {
  d: path("M5 8h14l-.75 11a2 2 0 0 1-2 2h-8.5a2 2 0 0 1-2-2Zm3.5 0V6.5a3.5 3.5 0 0 1 7 0V8");
}

</style>
