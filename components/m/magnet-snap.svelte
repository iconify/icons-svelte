<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1eq32bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:magnet-snap" {...props}></Icon>
<style>
:global(.j1eq32bjx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5h4v7a2.5 2.5 0 0 0 5 0v-7h4v7a6.5 6.5 0 0 1-13 0Zm0 3.5h4m5 0h4M3 20.5h4m3 0h4m3 0h4");
}

</style>
