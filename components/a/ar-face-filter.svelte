<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="othkdac3b"/><path class="vrfblf_ag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ar-face-filter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.othkdac3b) {
  d: path("M2.5 14a7 7 0 1 0 14 0a7 7 0 1 0-14 0M7 13h.01M12 13h.01");
}

:global(.vrfblf_ag) {
  d: path("M6.75 16.75q2.75 2.25 5.5 0M18.5 2.5Q19 5.5 22 6q-3 .5-3.5 3.5Q18 6.5 15 6q3-.5 3.5-3.5");
}

</style>
