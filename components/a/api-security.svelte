<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wulqo-bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:api-security" {...props}></Icon>
<style>
:global(.wulqo-bjv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5c-2 0-2 1-2 3v3c0 1.5-1 2.5-2 2.5c1 0 2 1 2 2.5v3c0 2 0 3 2 3m11-17c2 0 2 1 2 3v3c0 1.5 1 2.5 2 2.5c-1 0-2 1-2 2.5v3c0 2 0 3-2 3M11.125 11h1.75a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 12.875 17h-1.75A2.625 2.625 0 0 1 8.5 14.375v-.75A2.625 2.625 0 0 1 11.125 11M10 11V9a2 2 0 0 1 4 0v2");
}

</style>
