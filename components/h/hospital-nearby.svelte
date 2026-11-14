<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkfecxb8k"/><path class="vuom80bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hospital-nearby" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lkfecxb8k) {
  d: path("M3 21.5V9h5V3.5h8V9h5v12.5ZM12 9v5.5m-2.75-2.75h5.5");
}

:global(.vuom80bix) {
  d: path("M10 21.5v-4h4v4M5.5 13h.01m-.01 4h.01m12.99-4h.01m-.01 4h.01");
}

</style>
