<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brgnsx_vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:metronome" {...props}></Icon>
<style>
:global(.brgnsx_vb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.664 3h2.672a2.625 2.625 0 0 1 2.577 2.124l2.479 12.75A2.625 2.625 0 0 1 15.815 21h-7.63a2.625 2.625 0 0 1-2.577-3.126l2.479-12.75A2.625 2.625 0 0 1 10.664 3M6 17h12m-6 0l3.25-10.5");
}

</style>
