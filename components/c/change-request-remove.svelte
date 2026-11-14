<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qyi7-c6de"/><path class="u6wy7cjtk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:change-request-remove" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qyi7-c6de) {
  d: path("M18 20.829v.671H4v-19h9l5 5v7.729");
}

:global(.u6wy7cjtk) {
  d: path("M13 2.5v5h5M7.5 11h7m-7 4H11m4 3h6");
}

</style>
