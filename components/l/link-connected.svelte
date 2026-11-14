<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xsv8hdbpm"/><path class="ze0cfd9xh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:link-connected" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xsv8hdbpm) {
  d: path("M10.052 17.638a6 6 0 1 1 3.341-3.008");
}

:global(.ze0cfd9xh) {
  d: path("M13.948 6.362a6 6 0 1 1-3.341 3.008");
}

</style>
