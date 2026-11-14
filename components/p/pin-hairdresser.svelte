<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-3bt1blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-hairdresser" {...props}></Icon>
<style>
:global(.c-3bt1blt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 18a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m10 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M8.5 15.75l9-12.25m-2 12.25L6.5 3.5");
}

</style>
