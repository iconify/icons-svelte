<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb27nx05f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blood-pressure-cuff" {...props}></Icon>
<style>
:global(.cb27nx05f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h6a3.5 3.5 0 0 1 3.5 3.5v1A3.5 3.5 0 0 1 12 11H6a3.5 3.5 0 0 1-3.5-3.5v-1A3.5 3.5 0 0 1 6 3m11.5 10.5c2 0 3.5 2.25 3.5 4.25c0 2.15-1.5 3.75-3.5 3.75S14 19.9 14 17.75c0-2 1.5-4.25 3.5-4.25M6.5 3v8M9 11c0 4.5 1.5 6.5 5 6.75m3.5-4.25v-2");
}

</style>
