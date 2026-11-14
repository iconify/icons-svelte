<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie2ysrxpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:corner-radius-tool" {...props}></Icon>
<style>
:global(.ie2ysrxpk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V11a8 8 0 0 1 8-8h10m-3 12v6m-3-3h6");
}

</style>
