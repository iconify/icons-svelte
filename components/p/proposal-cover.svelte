<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="khtiqsqaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:proposal-cover" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.khtiqsqaa) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M9.25 11.25h5.5A1.75 1.75 0 0 1 16.5 13v.25A1.75 1.75 0 0 1 14.75 15h-5.5a1.75 1.75 0 0 1-1.75-1.75V13a1.75 1.75 0 0 1 1.75-1.75M7.5 18h5");
}

:global(.w_a5jubhp) {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
