<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvn-2jbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:motocross-boots" {...props}></Icon>
<style>
:global(.lvn-2jbze) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h10l-1 4v5.5l5 2a2.5 2.5 0 0 1 2 2.5v1H5.5l1-11Zm.5 15v3H21v-3M6.25 10.5H14");
}

</style>
