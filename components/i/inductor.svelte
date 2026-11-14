<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uues89bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:inductor" {...props}></Icon>
<style>
:global(.uues89bex) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h2m0 0A2.25 3 0 0 1 9 14a2.25 3 0 0 1 4.5 0a2.25 3 0 0 1 4.5 0a2.25 3 0 0 1 4 0");
}

</style>
