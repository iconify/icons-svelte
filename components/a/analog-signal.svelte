<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce0u-0j5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:analog-signal" {...props}></Icon>
<style>
:global(.ce0u-0j5b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12c2.5-7.5 6-7.5 9.5 0s7 7.5 9.5 0");
}

</style>
