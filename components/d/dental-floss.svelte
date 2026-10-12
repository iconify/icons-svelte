<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lsrx3cb0x"/><path class="w47cr_afy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dental-floss" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lsrx3cb0x) {
  width: 12.5px;
  height: 12.75px;
  x: 3.75px;
  y: 8.5px;
  rx: 3px;
}

:global(.w47cr_afy) {
  d: path("M3.75 12.75h12.5M10 8.5v-2C10 4.25 11.5 3 13.25 3C15.5 3 16 5.5 18 5.5c1.25 0 2-.5 2.5-1.25");
}

</style>
