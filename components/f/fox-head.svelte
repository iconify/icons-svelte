<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfc960_yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fox-head" {...props}></Icon>
<style>
:global(.jfc960_yr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 20.5l-5-6L3 12l1-9l5.5 4.5h5L20 3l1 9l-4 2.5Zm-2.75-8.75h.01m5.49 0h.01");
}

</style>
