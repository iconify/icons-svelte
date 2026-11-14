<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1aogdbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:electromagnet" {...props}></Icon>
<style>
:global(.u1aogdbmj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3v11a6 6 0 0 0 12 0V3M3 6l7.5 3M3 10.5l7.5 3");
}

</style>
