<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ifbg6mbut"/><path class="epkjncc5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:espresso-machine" {...props}></Icon>
<style>
:global(.epkjncc5t) {
  d: path("M12 8.5v1.75H8V8.5m0 1.25L3.25 11.5M7 13.25h5.5v2.25a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ifbg6mbut) {
  d: path("M3.5 3h17v17.5h-17v-3h13v-9h-13Z");
}

</style>
