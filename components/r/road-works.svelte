<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukth_xeaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:road-works" {...props}></Icon>
<style>
:global(.ukth_xeaf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20H3l1.75-7.5L6.5 20h11l1.75-7.5L21 20h.5M7 5h10v5.5H7Zm5 5.5V20m-3.75-9.5l2-5.5m3.5 0l2 5.5");
}

</style>
