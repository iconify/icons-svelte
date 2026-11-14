<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="feengacwm"/><path class="ephyckbdp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hourglass-ancient" {...props}></Icon>
<style>
:global(.ephyckbdp) {
  d: path("m16 14.5l-4-10v10zm-4 0l-5.5 1.25");
}

:global(.feengacwm) {
  d: path("M2.5 14.5a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
