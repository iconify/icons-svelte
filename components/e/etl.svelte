<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk0_nuilx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:etl" {...props}></Icon>
<style>
:global(.hk0_nuilx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5H3v8h3.5M3 7.5h3m2.5-4H14m-2.75 0v8m5.25-8v8h4M3 17.5h17.5m-3-3l3 3l-3 3");
}

</style>
