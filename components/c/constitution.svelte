<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxblkv2yz"/><path class="u7rd14ldy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:constitution" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u7rd14ldy) {
  d: path("M10 17.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.zxblkv2yz) {
  d: path("M7 6.5h-.5a2 2 0 0 1 0-4h11a2 2 0 0 1 0 4H17V19a2.5 2.5 0 0 1-2.5 2.5h-8a2 2 0 0 1 0-4H7Zm2.5 3h5m-5 3h3");
}

</style>
