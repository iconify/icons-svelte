<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q7cxk0y8g"/><path class="rs768sbdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:exit-ramp-right" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q7cxk0y8g) {
  d: path("M7 21.5v-19M7 18c0-5 1.5-7 4-9.5L16.5 3");
}

:global(.rs768sbdo) {
  d: path("M12 3h4.5v4.5");
}

</style>
