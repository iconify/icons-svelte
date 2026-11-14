<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ozzb4qbps"/><path class="dhqnqfb6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cast-net" {...props}></Icon>
<style>
:global(.dhqnqfb6x) {
  d: path("M6.75 13.5q5.25 2 10.5 0M12 2.5v1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ozzb4qbps) {
  d: path("M12 3.5L4 19q8 3 16 0Zm0 0L9.25 20M12 3.5L14.75 20");
}

</style>
