<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="qj948r1mx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:jet-engine-front" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.qj948r1mx) {
  d: path("M12 12c-3.5-2.5-3-7 0-7s3.5 4.5 0 7m0 0c4-1.75 7.5.9 6 3.5c-1.5 2.5-5.5.75-6-3.5m0 0c-.5 4.25-4.5 6-6 3.5c-1.5-2.6 2-5.25 6-3.5");
}

</style>
