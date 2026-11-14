<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8jzdgbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:descender" {...props}></Icon>
<style>
:global(.i8jzdgbep) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 8v10a3.5 3.5 0 0 1-7 0m7-14h.01M4 15h16");
}

</style>
