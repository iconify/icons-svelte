<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpe8u9bbt"/><path class="wdzw1bb0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pharmacy-drive-thru" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wdzw1bb0e) {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m3.5-1v-2.25l1.75-2.5h4l2 2.5v2.25Zm2 2h.01m3.74 0h.01");
}

:global(.wpe8u9bbt) {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.9m-15-.9v9.5h6.9");
}

</style>
