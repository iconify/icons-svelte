<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6jcs4qjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:grass-shears" {...props}></Icon>
<style>
:global(.j6jcs4qjl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.25 7L21 18.5M11 5.75L18.5 21");
}

</style>
