<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i71c4ub8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:couple-heart" {...props}></Icon>
<style>
:global(.i71c4ub8w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M3 21c0-2.5 1.75-3.75 4-3.75s4 1.25 4 3.75m3.25-9.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M13 21c0-2.5 1.75-3.75 4-3.75s4 1.25 4 3.75M12 9L8.75 5.75A2.1 2.1 0 1 1 12 3a2.1 2.1 0 1 1 3.25 2.75Z");
}

</style>
