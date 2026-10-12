<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2xb18bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ladle" {...props}></Icon>
<style>
:global(.k2xb18bli) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h10a5 5 0 0 1-10 0m2 2.25h6m2-2.25L17.9 5.2a1.5 1.5 0 0 1 2.55 1.6");
}

</style>
