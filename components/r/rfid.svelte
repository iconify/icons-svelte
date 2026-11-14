<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ycvha4bau"/><path class="tj32t6iek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rfid" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tj32t6iek) {
  d: path("M6.25 10.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m9-1a4.5 4.5 0 0 1 0 7m3-9.5a7 7 0 0 1 0 11");
}

:global(.ycvha4bau) {
  d: path("m3.763 8.487l2.75-2.75a1.75 1.75 0 0 1 2.474 0l2.75 2.75a1.75 1.75 0 0 1 .513 1.238v8.525A1.75 1.75 0 0 1 10.5 20H5a1.75 1.75 0 0 1-1.75-1.75V9.725a1.75 1.75 0 0 1 .513-1.238");
}

</style>
