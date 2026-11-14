<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xxo-6fbce"/><path class="td6gz_brw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:contact-linked" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.td6gz_brw) {
  d: path("M12.75 16h3A2.25 2.25 0 0 1 18 18.25a2.25 2.25 0 0 1-2.25 2.25h-3a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 12.75 16");
}

:global(.xxo-6fbce) {
  d: path("M4.25 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2.5 13a3.75 3.5 0 0 1 7.5 0m5.75-8.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M14 13a3.75 3.5 0 0 1 7.5 0M7.75 16h3A2.25 2.25 0 0 1 13 18.25a2.25 2.25 0 0 1-2.25 2.25h-3a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 7.75 16");
}

</style>
