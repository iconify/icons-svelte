<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yequtdbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pit-lollipop" {...props}></Icon>
<style>
:global(.yequtdbqi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6 6v7m-3-13h6m-6 13h6");
}

</style>
