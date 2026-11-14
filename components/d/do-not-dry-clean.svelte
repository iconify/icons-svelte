<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfxmnpbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:do-not-dry-clean" {...props}></Icon>
<style>
:global(.jfxmnpbuh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0M4 4l16 16m0-16L4 20");
}

</style>
