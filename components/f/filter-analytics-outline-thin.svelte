<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vrfr-0-4l"/><path class="ib0uz7xmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:filter-analytics-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ib0uz7xmw) {
  d: path("M10 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vrfr-0-4l) {
  d: path("M3 4h18l-7 7v5h-4v-5Z");
}

</style>
