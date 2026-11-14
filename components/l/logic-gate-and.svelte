<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kum1teb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:logic-gate-and" {...props}></Icon>
<style>
:global(.kum1teb4t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h6a7 7 0 0 1 0 14H6ZM2.5 9H6m-3.5 6H6m13-3h2.5");
}

</style>
