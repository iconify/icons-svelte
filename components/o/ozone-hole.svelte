<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxtia4tkm"/><path class="x-knmab1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ozone-hole" {...props}></Icon>
<style>
:global(.dxtia4tkm) {
  d: path("M6 14a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-knmab1h) {
  d: path("M9.5 14a2.5 6 0 1 0 5 0a2.5 6 0 1 0-5 0M6 14h12M3.073 10.751a9.5 9.5 0 0 1 5.678-5.678m6.498 0a9.5 9.5 0 0 1 5.678 5.678");
}

</style>
