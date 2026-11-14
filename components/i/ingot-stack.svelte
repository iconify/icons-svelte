<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km6g3gbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ingot-stack" {...props}></Icon>
<style>
:global(.km6g3gbwz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 17.5l2-5.5h4.25l2 5.5Zm10.75 0l2-5.5h4.25l2 5.5Zm-6-5.5l2-5.5h5.5l2 5.5Z");
}

</style>
