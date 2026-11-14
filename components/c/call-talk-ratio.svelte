<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd5abtb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:call-talk-ratio" {...props}></Icon>
<style>
:global(.fd5abtb6z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H6l-3 3zm13.75 7a2 2 0 0 1 2-2h.75a2 2 0 0 1 2 2v8.5L19 18h-.25a2 2 0 0 1-2-2Z");
}

</style>
