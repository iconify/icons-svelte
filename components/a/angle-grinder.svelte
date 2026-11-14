<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="likinw94s"/><path class="fhz-erbhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:angle-grinder" {...props}></Icon>
<style>
:global(.fhz-erbhy) {
  d: path("M15 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.likinw94s) {
  d: path("M5 10.5h4a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 9 15.5H5A2.5 2.5 0 0 1 2.5 13A2.5 2.5 0 0 1 5 10.5m6.5 2.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0M7 10.5V5");
}

</style>
