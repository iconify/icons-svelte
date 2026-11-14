<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttmqoubtl"/><path class="x-4456bpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:axial-tilt" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ttmqoubtl) {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0m9.75-9.25l-7.5 18.5");
}

:global(.x-4456bpn) {
  d: path("M6 12a6 2 0 1 0 12 0a6 2 0 1 0-12 0m6-9a9 9 0 0 1 3.5.75");
}

</style>
