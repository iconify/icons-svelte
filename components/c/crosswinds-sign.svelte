<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzbu1hbra"/><path class="vhqmbibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crosswinds-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nzbu1hbra) {
  d: path("M7.375 2.5h9.25A4.375 4.375 0 0 1 21 6.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 13.125v-6.25A4.375 4.375 0 0 1 7.375 2.5M12 17.5v4");
}

:global(.vhqmbibcr) {
  d: path("M6 8h8a1.25 1.25 0 1 0-1.25-1.25M6 11h6m-6 3h10a1.25 1.25 0 1 0-1.25-1.25");
}

</style>
