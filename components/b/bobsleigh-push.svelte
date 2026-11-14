<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp7xw4b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bobsleigh-push" {...props}></Icon>
<style>
:global(.sp7xw4b6s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h10c3.5 0 6 2 6.5 5.5H4Zm1 8.5h8M4 7L2.5 3.5m12.5 15h6m-2.75-2.75L21 18.5l-2.75 2.75");
}

</style>
