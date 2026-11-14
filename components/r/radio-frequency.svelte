<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmhdq56bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:radio-frequency" {...props}></Icon>
<style>
:global(.pmhdq56bg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2v10.5m3.5-16a5 5 0 0 1 0 7m-7-7a5 5 0 0 0 0 7M18 3a8.5 8.5 0 0 1 0 12M6 3a8.5 8.5 0 0 0 0 12");
}

</style>
