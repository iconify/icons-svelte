<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5659k6od"/><path class="x0m_cmolk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:earth-leaf" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r5659k6od) {
  d: path("M2.5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

:global(.x0m_cmolk) {
  d: path("M6.5 9.5a3 7 0 1 0 6 0a3 7 0 1 0-6 0m-4 0h14M16 20c0-3.5 1.5-5 5-5c0 3.5-1.5 5-5 5m0 0l-1.25 1.25");
}

</style>
