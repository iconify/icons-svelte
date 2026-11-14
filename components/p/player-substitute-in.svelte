<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc4eoccpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:player-substitute-in" {...props}></Icon>
<style>
:global(.vc4eoccpe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M8.5 20c0-3.5 2.75-6.5 6.5-6.5s6.5 3 6.5 6.5M2.5 7h6.25M6 4.25L8.75 7L6 9.75");
}

</style>
