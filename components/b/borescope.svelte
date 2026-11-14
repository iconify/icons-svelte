<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asfp04bdf"/><path class="lz19wkktb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:borescope" {...props}></Icon>
<style>
:global(.asfp04bdf) {
  d: path("M9.5 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lz19wkktb) {
  d: path("M12.5 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-6-9l9 9M2.5 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
