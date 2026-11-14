<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etj810igh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:capture-zone" {...props}></Icon>
<style>
:global(.etj810igh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18a9 3.25 0 1 0 18 0a9 3.25 0 1 0-18 0m9 0V3m0 .5h7l-2 2.75L19 9h-7");
}

</style>
