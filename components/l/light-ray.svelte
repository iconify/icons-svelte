<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7zqflb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:light-ray" {...props}></Icon>
<style>
:global(.j7zqflb3g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m6.25-3.75L21 3m-6.75 11.25l5-5m-9.5.5l5-5");
}

</style>
