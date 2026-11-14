<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blbrfobyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dew" {...props}></Icon>
<style>
:global(.blbrfobyw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19c0-9 7-16 16-16c0 9-7 16-16 16m0 0l9-9m6.25 4.5s-2.75 3-2.75 4.5a2.75 2.75 0 0 0 5.5 0c0-1.5-2.75-4.5-2.75-4.5");
}

</style>
