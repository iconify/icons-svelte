<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v01g4fndv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fishing-zone" {...props}></Icon>
<style>
:global(.v01g4fndv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.65 2.644a9.5 9.5 0 0 1 7.706 7.706m0 3.3a9.5 9.5 0 0 1-7.706 7.706m-3.3 0a9.5 9.5 0 0 1-7.706-7.706m0-3.3a9.5 9.5 0 0 1 7.706-7.706M6 12c2-4.5 6.5-4.5 8.5 0L18 9.5v5L14.5 12c-2 4.5-6.5 4.5-8.5 0m3.25 0h.01");
}

</style>
