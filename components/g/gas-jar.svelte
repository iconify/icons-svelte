<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cic9bggnc"/><path class="lafs_4bqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gas-jar" {...props}></Icon>
<style>
:global(.cic9bggnc) {
  d: path("M5.5 3H7v16.5a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V3h1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lafs_4bqt) {
  d: path("M9.75 13a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
