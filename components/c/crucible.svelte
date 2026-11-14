<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="whzvonk0o"/><path class="kgd64sn1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crucible" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kgd64sn1o) {
  d: path("M7 10.5c2-1 3 1 5 0s3 1 5 0M10 4c-.75-.75.75-1.25 0-2m4 2c-.75-.75.75-1.25 0-2");
}

:global(.whzvonk0o) {
  d: path("M5 6.5h14L17.5 18a2.5 2.5 0 0 1-2.5 2.5H9A2.5 2.5 0 0 1 6.5 18Z");
}

</style>
