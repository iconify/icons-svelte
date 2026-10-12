<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q0r-77kgr"/><path class="m0tqvhb2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:biryani-pot" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0tqvhb2a) {
  d: path("M5.5 14.25q1.08 1 2.17 0q1.08 1 2.17 0q1.08 1 2.17 0q1.08 1 2.17 0q1.08 1 2.17 0q1.08 1 2.17 0");
}

:global(.q0r-77kgr) {
  d: path("M3.75 11.25h16.5v2a8.25 8 0 0 1-16.5 0Zm1.5 0a6.75 4 0 0 1 13.5 0Zm-2.5 0h18.5m-12.5-6c-.9-.75.9-1.5 0-2.5M12 5c-.9-.75.9-1.5 0-2.25m3.25 2.5c-.9-.75.9-1.5 0-2.5");
}

</style>
