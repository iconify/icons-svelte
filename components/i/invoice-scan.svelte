<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0u40_kgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:invoice-scan" {...props}></Icon>
<style>
:global(.y0u40_kgl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h13V21l-2.25-1.5L14 21l-2-1.5l-2 1.5l-2.25-1.5L5.5 21Zm3 4.5h7m-7 9H13M2.5 11.5h19");
}

</style>
