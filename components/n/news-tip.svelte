<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwpya1bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:news-tip" {...props}></Icon>
<style>
:global(.wwpya1bat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-2.5 13c0-4 2.5-6 6-6s6 2 6 6M17 12V9.5a3.5 3.5 0 1 1 3 0V12Zm0 3h3");
}

</style>
