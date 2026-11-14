<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4ey99b0m"/><path class="ygukbt2zh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:patient-wristband" {...props}></Icon>
<style>
:global(.h4ey99b0m) {
  d: path("M2.5 12c0-3.5 4.25-5.5 9.5-5.5s9.5 2 9.5 5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ygukbt2zh) {
  d: path("M8.25 11.5h7.5a1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-3.5a1.75 1.75 0 0 1 1.75-1.75M2.5 12c0 1.5 1 2.75 3 3.5m16-3.5c0 1.5-1 2.75-3 3.5M8.75 14h6.5m-6.5 2.25h4");
}

</style>
