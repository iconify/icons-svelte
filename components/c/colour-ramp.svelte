<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmr14l3ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:colour-ramp" {...props}></Icon>
<style>
:global(.jmr14l3ik) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17h19V7ZM9 17v-3.5m6.25 3.5v-6.75");
}

</style>
