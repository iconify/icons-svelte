<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkpxhpb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pit-exit-light" {...props}></Icon>
<style>
:global(.wkpxhpb0y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4 4V18m-9.5 3H8v-3h13.5M3 6.5h2.25m13.5 0H21");
}

</style>
