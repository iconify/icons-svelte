<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qob-g5brz"/><path class="ix2f4s1as"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cave-interior" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ix2f4s1as) {
  d: path("M8 5.25L9.5 9.5L11 4m2 0l1.5 5.5L16 5.25");
}

:global(.qob-g5brz) {
  d: path("M2.5 20.5h19M5 20.5V11a7 7 0 0 1 14 0v9.5");
}

</style>
