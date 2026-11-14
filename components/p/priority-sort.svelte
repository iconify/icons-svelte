<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7boeowzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:priority-sort" {...props}></Icon>
<style>
:global(.d7boeowzt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6h11M3 12h8m-8 6h5M18.5 4v16m-3-3l3 3l3-3");
}

</style>
