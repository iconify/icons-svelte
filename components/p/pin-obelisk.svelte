<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp5nrgwbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-obelisk" {...props}></Icon>
<style>
:global(.bp5nrgwbw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21L9.5 6L12 2.5L14.5 6L16 21M4.5 21h15M9.5 6h5");
}

</style>
