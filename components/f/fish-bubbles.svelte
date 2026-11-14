<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5fparmnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fish-bubbles" {...props}></Icon>
<style>
:global(.f5fparmnc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 15c-3-5-10.5-5-13.5 0L3 11v8l4.5-4c3 5 10.5 5 13.5 0m-6.5-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0M19 3h.01M17.5 14.5h.01");
}

</style>
