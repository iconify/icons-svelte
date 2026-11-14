<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiqfsxbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crate" {...props}></Icon>
<style>
:global(.jiqfsxbkd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3.5h12.75A2.625 2.625 0 0 1 21 6.125v11.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 17.875V6.125A2.625 2.625 0 0 1 5.625 3.5M3 8h18M3 16h18M3 16l18-8");
}

</style>
