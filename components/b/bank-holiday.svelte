<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h3zwapb2i"/><path class="cx88otb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bank-holiday" {...props}></Icon>
<style>
:global(.cx88otb8c) {
  d: path("M10 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-4.5v1m0 7v1M7.5 15h1m7 0h1m-7.75-3.25l.75.75m5.75-.75l-.75.75m-5.75 5.75l.75-.75m5.75.75l-.75-.75");
}

:global(.h3zwapb2i) {
  d: path("M7 4.5h10A3.5 3.5 0 0 1 20.5 8v10a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V8A3.5 3.5 0 0 1 7 4.5m1-2V6m8-3.5V6M3.5 8h17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
