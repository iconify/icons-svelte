<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0up1jxkc"/><path class="dlpk0pdin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mail-open" {...props}></Icon>
<style>
:global(.dlpk0pdin) {
  d: path("m3.5 10.5l8.5 5l8.5-5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i0up1jxkc) {
  d: path("m3 10l9-6l9 6v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
