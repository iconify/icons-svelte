<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k36313b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:feather-nature" {...props}></Icon>
<style>
:global(.k36313b_z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 3.5C21 11 15.5 16.5 7 17c0-4 1.5-6.5 3.5-8l2.5.5l-1-2c2.5-2.5 5.5-3.75 8.5-4Zm-17 17l13-13");
}

</style>
