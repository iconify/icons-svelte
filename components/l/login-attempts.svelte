<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eck8rtbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:login-attempts" {...props}></Icon>
<style>
:global(.eck8rtbzu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6v7M9 6v7m3.5-7v7M16 6v7M3.5 11L18 8m0 6.75v3.5M18 21h.01");
}

</style>
