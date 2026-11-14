<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7ezb-v1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gaff-sail" {...props}></Icon>
<style>
:global(.d7ezb-v1j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5V19m.829-10.415l9.256-4.627a1.5 1.5 0 0 1 2.16 1.169l1.062 9.201A1.5 1.5 0 0 1 16.817 16H6.5A1.5 1.5 0 0 1 5 14.5V9.927a1.5 1.5 0 0 1 .829-1.342M5 9l13-6.5M5 16h15M3 19h18l-2 2.5H5Z");
}

</style>
