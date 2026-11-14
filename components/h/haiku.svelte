<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mymuthxif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:haiku" {...props}></Icon>
<style>
:global(.mymuthxif) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5h11m-11 6h18m-18 6h11m3-11q0-5.25 4.5-6q0 5.25-4.5 6");
}

</style>
