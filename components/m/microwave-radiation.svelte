<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1js_etav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:microwave-radiation" {...props}></Icon>
<style>
:global(.w1js_etav) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6q3-3 6 0t6 0t6 0M3 12q3-3 6 0t6 0t6 0M3 18q3-3 6 0t6 0t6 0");
}

</style>
