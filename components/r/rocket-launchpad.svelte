<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbshtobkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rocket-launchpad" {...props}></Icon>
<style>
:global(.mbshtobkw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19M5.5 5H6a1.5 1.5 0 0 1 1.5 1.5V19A1.5 1.5 0 0 1 6 20.5h-.5A1.5 1.5 0 0 1 4 19V6.5A1.5 1.5 0 0 1 5.5 5m2 5h6m0 10.5V9c0-3 2.5-5.5 2.5-5.5S18.5 6 18.5 9v11.5m-5-5l-2 2.5v2.5m7-5l2 2.5v2.5");
}

</style>
