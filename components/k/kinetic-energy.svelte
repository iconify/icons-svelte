<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1r6f1bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kinetic-energy" {...props}></Icon>
<style>
:global(.o1r6f1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0M4 8.5h3M2.5 12h3.25M4 15.5h3");
}

</style>
