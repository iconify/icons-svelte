<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emmp1yrxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ip-allowlist" {...props}></Icon>
<style>
:global(.emmp1yrxs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6.5h.01M8 6.5h12.5m-16 5h.01m3.49 0h12.5M14.75 18l2 2L21 15.75");
}

</style>
