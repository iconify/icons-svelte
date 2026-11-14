<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a9r_v3b3b"/><path class="okohc-b1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chewable-tablet" {...props}></Icon>
<style>
:global(.a9r_v3b3b) {
  d: path("M15.25 3.25a8 8 0 1 0 4.25 4.5a3.5 3.5 0 0 1-4.25-4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.okohc-b1j) {
  d: path("M4 10.5v3a8 8 0 0 0 16 0v-3");
}

</style>
