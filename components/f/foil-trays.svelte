<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxq5bqfvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:foil-trays" {...props}></Icon>
<style>
:global(.wxq5bqfvm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h2L6 10.5h12L19.5 6h2m-19 7.5h2L6 18h12l1.5-4.5h2");
}

</style>
