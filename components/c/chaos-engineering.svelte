<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_h0-4brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chaos-engineering" {...props}></Icon>
<style>
:global(.i_h0-4brt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h9v6H3Zm1.5 6h10v6h-10Zm5.6 12H2.5v-6h10v3.1m7-4.1L16 18.25h4l-2.75 3.25");
}

</style>
