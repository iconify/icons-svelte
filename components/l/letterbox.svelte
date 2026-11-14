<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nxeu9zk9n"/><path class="njoe09d5e"/><path class="g9q6iz3ji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:letterbox" {...props}></Icon>
<style>
:global(.g9q6iz3ji) {
  d: path("m9 9.5l3 3l3-3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.njoe09d5e) {
  d: path("M9 9.5V16h6V9.5");
}

:global(.nxeu9zk9n) {
  d: path("M5 21.5V4a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 19 4v17.5m-16.5 0h19M8 9.5h8");
}

</style>
