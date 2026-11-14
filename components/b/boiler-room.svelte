<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk14yjhev"/><path class="xf-fgjbvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boiler-room" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uk14yjhev) {
  d: path("M6 21.5V4a1.5 1.5 0 0 1 1.5-1.5h9A1.5 1.5 0 0 1 18 4v17.5m-15.5 0h19m-6-8h.01");
}

:global(.xf-fgjbvs) {
  d: path("M12 12c-1.5 0-2.25-1-2.25-2.25c0-1.5 1.25-2.25 1.5-3.75c.75.75 1 1.5 1 2.25c.5-.5.75-1 1-1.5c.75.75 1 2 1 3C14.25 11 13.5 12 12 12");
}

</style>
