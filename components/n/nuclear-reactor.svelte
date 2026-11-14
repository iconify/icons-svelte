<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdmsgpbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nuclear-reactor" {...props}></Icon>
<style>
:global(.wdmsgpbex) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21V11a8 8 0 0 1 16 0v10Zm5-9v6m3-6v6m3-6v6");
}

</style>
