<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rln_ziztq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:account-industry" {...props}></Icon>
<style>
:global(.rln_ziztq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V11l5-3v3l5-3v3h2.5V3.5h4V21Zm4-5.5h.01m3.99 0h.01m3.99 0h.01");
}

</style>
