<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w16b0hkzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nasal-aspirator" {...props}></Icon>
<style>
:global(.w16b0hkzz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 8.25a6.5 6.5 0 1 0 4.5 4.5l5-8l-1.5-1.5ZM14 6.5l3.5 3.5");
}

</style>
