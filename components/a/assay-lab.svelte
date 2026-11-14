<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmmewachf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:assay-lab" {...props}></Icon>
<style>
:global(.lmmewachf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5V8L4 20h16L14 8V2.5m-5.5 0h7M2.5 20h19M7 14h10");
}

</style>
