<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ybuxbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:broadcast-message" {...props}></Icon>
<style>
:global(.i_ybuxbyb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9h4l10-5v16L9 15H5Zm5.5 6.75l1 4.25");
}

</style>
