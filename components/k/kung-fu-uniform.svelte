<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uh1n66bko"/><path class="a0ov50a-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kung-fu-uniform" {...props}></Icon>
<style>
:global(.a0ov50a-l) {
  d: path("m9.5 5l5 5.5V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uh1n66bko) {
  d: path("M8 5V2.5h8V5l4 1.5l1.5 7.5l-3 .5l-1-4V21h-11V10.5l-1 4l-3-.5L4 6.5Z");
}

</style>
