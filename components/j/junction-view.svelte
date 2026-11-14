<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wir3l_cnj"/><path class="l7cfyfi7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:junction-view" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l7cfyfi7s) {
  d: path("M5 9.75V5h4.75m4.5 0H19v4.75M7.5 21.5V16L3 11.5m13.5 10V16l4.5-4.5");
}

:global(.wir3l_cnj) {
  d: path("M12 20.5V12L5 5m7 7l7-7");
}

</style>
