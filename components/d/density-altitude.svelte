<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgulnd5en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:density-altitude" {...props}></Icon>
<style>
:global(.wgulnd5en) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 19.5l6-14l6 14ZM19 4.5v15M16.75 6.75L19 4.5l2.25 2.25m-4.5 10.5L19 19.5l2.25-2.25");
}

</style>
