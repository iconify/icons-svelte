<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwk4jomna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:animation-curve" {...props}></Icon>
<style>
:global(.mwk4jomna) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 18.5c5.5 0 4.5-13 10-13m-12 11l2 2l-2 2l-2-2Zm14-13l2 2l-2 2l-2-2Z");
}

</style>
