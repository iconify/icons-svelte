<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t3sn4fnir"/><path class="t551x-b_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:analytics-attribution-path" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t3sn4fnir) {
  d: path("M14 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

:global(.t551x-b_v) {
  d: path("M3.5 19.5L8 13l4 4l4-7.25M3.5 19.5h.01M8 13h.01M12 17h.01m5.74-10.5h.01");
}

</style>
