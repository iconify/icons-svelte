<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th7og062w"/><path class="v1ho1vr_n"/><path class="lw6lv_b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:outdoor-temperature" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lw6lv_b3z) {
  d: path("M14.25 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m2.25-4.25V3m0 9.75V14m4.25-5.5H22m-9.75 0H11m8.5-3l1-1m-7 1l-1-1m7 7l1 1m-7-1l-1 1");
}

:global(.th7og062w) {
  d: path("M4.5 13.5V5a2 2 0 0 1 4 0v8.5a3.75 3.75 0 1 1-4 0m2-5.5v7");
}

:global(.v1ho1vr_n) {
  fill: currentColor;
  d: path("M5 16.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
