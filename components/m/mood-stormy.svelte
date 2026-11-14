<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5p7_b1zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mood-stormy" {...props}></Icon>
<style>
:global(.l5p7_b1zt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 14h9a4 4 0 0 0 0-8A5.5 5.5 0 0 0 6 7.5A3.5 3.5 0 0 0 7.5 14Zm5.5 0l-2.5 4H14l-2.5 3.5");
}

</style>
