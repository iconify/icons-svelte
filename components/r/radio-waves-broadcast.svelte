<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfupezbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:radio-waves-broadcast" {...props}></Icon>
<style>
:global(.rfupezbba) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-2-3.5a5 5 0 0 0 0 7m7-7a5 5 0 0 1 0 7M5.75 5.75a8.75 8.75 0 0 0 0 12.5m12.5-12.5a8.75 8.75 0 0 1 0 12.5");
}

</style>
