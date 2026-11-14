<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i22n12bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:birthday-candle-number" {...props}></Icon>
<style>
:global(.i22n12bjv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 11.5L12.5 9v12m-3 0h6m-3-14.75C11.1 5.4 11 3.9 12.5 2c1.5 1.9 1.4 3.4 0 4.25Z");
}

</style>
