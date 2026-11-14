<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsja6ob9g"/><path class="bnjdu4b-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:poster-stand" {...props}></Icon>
<style>
:global(.bnjdu4b-s) {
  d: path("M12.75 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M8.5 13L11 9.5l2 2l1-1l1.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lsja6ob9g) {
  d: path("M8.25 2.5h7.5a1.75 1.75 0 0 1 1.75 1.75v9.5a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 8.25 2.5m3.75 13V19m-4.5 2.5a4.5 2.5 0 0 1 9 0Z");
}

</style>
