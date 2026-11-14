<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ic3xxhb-w"/><path class="wr03derli"/><path class="x-6arxdai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rgb-lights" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic3xxhb-w) {
  d: path("M6.5 8.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.wr03derli) {
  d: path("M2.75 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.x-6arxdai) {
  d: path("M10.25 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
