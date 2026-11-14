<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we5wslfmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:energy" {...props}></Icon>
<style>
:global(.we5wslfmp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m21.5 12l-6.25 1.25l3.5 5.5l-5.5-3.5L12 21.5l-1.25-6.25l-5.5 3.5l3.5-5.5L2.5 12l6.25-1.25l-3.5-5.5l5.5 3.5L12 2.5l1.25 6.25l5.5-3.5l-3.5 5.5ZM12 12h.01");
}

</style>
