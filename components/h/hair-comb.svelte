<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcpk16bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hair-comb" {...props}></Icon>
<style>
:global(.qcpk16bwq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 6h13.5A2.25 2.25 0 0 1 21 8.25a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 8.25A2.25 2.25 0 0 1 5.25 6m-.75 4.5v7m3-7v7m3-7v7m3-7v7m3-7v7m3-7v7");
}

</style>
