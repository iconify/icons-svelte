<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n21-2_bwv"/><path class="hrkp1hbry"/><path class="n1npu_o6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:day-surgery" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrkp1hbry) {
  fill: currentColor;
  d: path("M16.25 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.n1npu_o6y) {
  d: path("M17.75 14.25h.01m2.49 1h.01m.99 2.5h.01m-1.01 2.5h.01m-2.51 1h.01m-2.51-1h.01m-1.01-2.5h.01m.99-2.5h.01");
}

:global(.n21-2_bwv) {
  d: path("m9.25 9.25l5.5-4.75c.5-.5 1.25-.5 1.75 0s.5 1.25 0 1.75l-5.5 4.5ZM9 9l-3.5 3c-1.75 1.5-2 3.25-1 4.5l6.25-5.25Z");
}

</style>
