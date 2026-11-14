<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asx3i0b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:living-room" {...props}></Icon>
<style>
:global(.asx3i0b7i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18v6H3Zm2 0V8a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v3M6 17v3m12-3v3");
}

</style>
