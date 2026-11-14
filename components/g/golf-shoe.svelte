<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn8gpz9by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-shoe" {...props}></Icon>
<style>
:global(.bn8gpz9by) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16V6.5h5C9 10 12 11.5 16 12c3 .5 5 1.5 5 4h-1.5a1.5 1.5 0 0 1-3 0h-3a1.5 1.5 0 0 1-3 0h-3a1.5 1.5 0 0 1-3 0Z");
}

</style>
