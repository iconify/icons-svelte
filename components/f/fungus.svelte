<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9li-11ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fungus" {...props}></Icon>
<style>
:global(.c9li-11ig) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5c0-6.5 4-9 9-9s9 2.5 9 9Zm6 0l-.5 7A1.5 1.5 0 0 0 10 21h4a1.5 1.5 0 0 0 1.5-1.5l-.5-7");
}

</style>
