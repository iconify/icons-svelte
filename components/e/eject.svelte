<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvm1u_bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eject" {...props}></Icon>
<style>
:global(.vvm1u_bnt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.808 11.149L10.64 5.18a1.75 1.75 0 0 1 2.72 0l4.832 5.969A1.75 1.75 0 0 1 16.832 14H7.168a1.75 1.75 0 0 1-1.36-2.851M3.5 19.5h17");
}

</style>
