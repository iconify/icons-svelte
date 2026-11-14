<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oh_7r2dnp"/><path class="veju3ybsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fly-cast-loop" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oh_7r2dnp) {
  d: path("M3.5 21.5Q8 9 15 4.5m0 0c3-2 6.5-1.5 6.5 2s-5.5 4.5-8 4");
}

:global(.veju3ybsv) {
  d: path("M5.25 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
