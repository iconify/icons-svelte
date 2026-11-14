<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0p_eyqwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ocean-depth" {...props}></Icon>
<style>
:global(.b0p_eyqwb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6q3-2 6 0t6 0m-12 6q3-2 6 0t6 0m-12 6q3-2 6 0t6 0m5-14v16m-2.25-2.25L19.5 20l2.25-2.25");
}

</style>
