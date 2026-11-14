<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a25nqqbzb"/><path class="m8hvhdp_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gas-compressor-station" {...props}></Icon>
<style>
:global(.a25nqqbzb) {
  d: path("M7 15.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0m-4.5 0H7m10 0h4.5m-12.25-10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M12 8v2.25m0-5l1.5-1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m8hvhdp_r) {
  fill: currentColor;
  d: path("M12 13.25S10.5 15 10.5 16a1.5 1.5 0 0 0 3 0c0-1-1.5-2.75-1.5-2.75");
}

</style>
