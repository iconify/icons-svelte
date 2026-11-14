<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr5-ktbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-ingest" {...props}></Icon>
<style>
:global(.gr5-ktbtb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 9.5h11m-11 5h11m-11-5L7 5.5m3.5 9l-3.5 4M2.5 12h.01m2.74 0h.01M8 12h.01");
}

</style>
