<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnp29wpin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baby-bib" {...props}></Icon>
<style>
:global(.hnp29wpin) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7c-2.5 6-1 14 7 14s9.5-8 7-14h-3a4 4 0 0 1-8 0Zm0 0c0-5 14-5 14 0");
}

</style>
