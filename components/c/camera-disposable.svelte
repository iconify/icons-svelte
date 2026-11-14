<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrk880dkh"/><path class="rfl0cwb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camera-disposable" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rfl0cwb4z) {
  d: path("M11.75 12.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

:global(.zrk880dkh) {
  d: path("M6 6h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 6m-3.5 5l5-5m-5 9l9-9");
}

</style>
