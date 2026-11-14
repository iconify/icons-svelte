<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wymarjbdf"/><path class="w5in3xb1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ground-support-mesh" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w5in3xb1h) {
  d: path("M3 13.5q9-8 18 0M3 8h.01M21 8h.01M12 4h.01");
}

:global(.wymarjbdf) {
  d: path("M3 8q9-8 18 0v11q-9-8-18 0Zm4.5-3v11M12 4v11m4.5-10v11");
}

</style>
