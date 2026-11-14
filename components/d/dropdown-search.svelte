<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vt4lcyb8a"/><path class="smp72abmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dropdown-search" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.smp72abmf) {
  d: path("m14.5 6.25l2 2l2-2m-4.75 11.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m4.75 2L20.75 22");
}

:global(.vt4lcyb8a) {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v.75A4.375 4.375 0 0 1 17.125 12H6.875A4.375 4.375 0 0 1 2.5 7.625v-.75A4.375 4.375 0 0 1 6.875 2.5");
}

</style>
