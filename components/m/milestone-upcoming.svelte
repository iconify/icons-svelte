<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqvwv7bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:milestone-upcoming" {...props}></Icon>
<style>
:global(.mqvwv7bsg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5V3m0 .5h9l-2 3.25L13 10H4m9.5 7H21m-2.5-2.5L21 17l-2.5 2.5");
}

</style>
