<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2396gb4u"/><path class="gtk9mryps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:artistic-swimming" {...props}></Icon>
<style>
:global(.a2396gb4u) {
  d: path("M2.5 18.5q2.375-2 4.75 0t4.75 0t4.75 0t4.75 0");
}

:global(.gtk9mryps) {
  d: path("M12 18.5L7.25 5l-1-2.5m5.75 16L16.75 5l1-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
