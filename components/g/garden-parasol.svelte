<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwwbx-b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garden-parasol" {...props}></Icon>
<style>
:global(.fwwbx-b-b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5C4 5.5 7.5 3 12 3s8 2.5 9 7.5q-3-1.5-6 0q-3-1.5-6 0q-3-1.5-6 0m9-.75V21m-4 0h8");
}

</style>
