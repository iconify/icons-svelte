<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kab52c2ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garden-shredder" {...props}></Icon>
<style>
:global(.kab52c2ew) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h17L17 11v5H7v-5Zm4-5l2 5m7-5l-2.5 5M15.25 5l3-.75M9 18.75v3m3-3v3m3-3v3");
}

</style>
