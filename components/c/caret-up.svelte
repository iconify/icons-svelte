<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ozxfamn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:caret-up" {...props}></Icon>
<style>
:global(.i6ozxfamn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.099 8.684l3.06 3.295A1.5 1.5 0 0 1 15.06 14.5H8.94a1.5 1.5 0 0 1-1.099-2.521l3.06-3.295a1.5 1.5 0 0 1 2.198 0");
}

</style>
