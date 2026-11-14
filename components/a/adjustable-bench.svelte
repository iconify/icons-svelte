<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xayongb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:adjustable-bench" {...props}></Icon>
<style>
:global(.xayongb2t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h12v3h-12Zm12 0l4.25-7.5l2.5 1.5l-4.75 7.5Zm-10 3v6.5m8-6.5v6.5");
}

</style>
