<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0_rjvhpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:loading-bars" {...props}></Icon>
<style>
:global(.l0_rjvhpc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 20v-6m6.5 6V9m6.5 11V4");
}

</style>
