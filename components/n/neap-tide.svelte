<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slajc9x0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:neap-tide" {...props}></Icon>
<style>
:global(.slajc9x0a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 3.5a5 5 0 1 0 0 8a5 5 0 0 1 0-8M3 17q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0M3 20.5q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
