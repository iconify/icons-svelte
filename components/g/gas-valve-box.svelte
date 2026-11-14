<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wb2utu0dv"/><path class="mfojgoj6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gas-valve-box" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mfojgoj6b) {
  d: path("M11.25 13h1.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 12.75 18h-1.5a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 11.25 13m3.25 2.5H21M12 13V8.5m-3.5 0h7");
}

:global(.wb2utu0dv) {
  d: path("M8.25 3h7.5A5.25 5.25 0 0 1 21 8.25v7.5A5.25 5.25 0 0 1 15.75 21h-7.5A5.25 5.25 0 0 1 3 15.75v-7.5A5.25 5.25 0 0 1 8.25 3M3 15.5h6.5");
}

</style>
