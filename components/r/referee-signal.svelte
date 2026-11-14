<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vacenfbma"/><path class="wks5ymklo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:referee-signal" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vacenfbma) {
  d: path("M7.75 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.wks5ymklo) {
  d: path("M5.25 21.5v-5a4 4 0 0 1 4-4h9.5v-9m-3.5 12v6");
}

</style>
