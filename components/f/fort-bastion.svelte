<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abuev3b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fort-bastion" {...props}></Icon>
<style>
:global(.abuev3b1j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V9h3v2.5h3V9h3v2.5h3V9h3l3.5 3.5V21ZM4.5 9V2.5m1.423.474l.827.276a.791.791 0 0 1 0 1.5l-.827.276A1.08 1.08 0 0 1 4.5 4a1.08 1.08 0 0 1 1.423-1.026");
}

</style>
