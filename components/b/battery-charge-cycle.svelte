<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezfqoj2xi"/><path class="w6td0rqjw"/><path class="govxk3bdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:battery-charge-cycle" {...props}></Icon>
<style>
:global(.ezfqoj2xi) {
  d: path("M5.072 8A8 8 0 0 1 20 12");
}

:global(.govxk3bdm) {
  d: path("M2 14.5L4 12l2.5 2.5M9.75 10h3a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 12.75 14h-3A1.75 1.75 0 0 1 8 12.25v-.5A1.75 1.75 0 0 1 9.75 10m6.75 1.25v1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w6td0rqjw) {
  d: path("M17.5 9.5L20 12l2-2.5M18.928 16A8 8 0 0 1 4 12");
}

</style>
