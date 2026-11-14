<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wf19-ebxl"/><path class="sa60rk6_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mine-headframe" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sa60rk6_y) {
  d: path("M4 20.5L8 7.25h8l4 13.25M12 7.25V20.5M6 14h12M2.5 20.5h19");
}

:global(.wf19-ebxl) {
  d: path("M6 5a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 6 5m7.5 0A2.25 2.25 0 1 0 18 5a2.25 2.25 0 1 0-4.5 0");
}

</style>
