<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kqstywb-q"/><path class="rhm7gfbii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cute-chick" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kqstywb-q) {
  d: path("m4.5 12.25l2.5 2.5l2.5-2.5l2.5 2.5l2.5-2.5l2.5 2.5l2.5-2.5c0 5.5-3.25 8.5-7.5 8.5s-7.5-3-7.5-8.5m5 0a4.75 4.75 0 1 1 5 0");
}

:global(.rhm7gfbii) {
  d: path("m18.112 7.379l.263.121a.826.826 0 0 1 0 1.5l-.263.121a.96.96 0 0 1-1.362-.871a.96.96 0 0 1 1.362-.871M13.25 7h.01");
}

</style>
