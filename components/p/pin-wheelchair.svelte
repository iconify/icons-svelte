<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hadfdob5y"/><path class="lhmj6kb2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-wheelchair" {...props}></Icon>
<style>
:global(.hadfdob5y) {
  d: path("M8.75 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 4.75v5.25h5.5l2.5 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lhmj6kb2n) {
  d: path("M14.639 12.111a5.5 5.5 0 1 1-8.223.503");
}

</style>
