<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vy3vtac-a"/><path class="rzsmeacgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lens-blower" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rzsmeacgn) {
  d: path("m11 11l5-4.25L17.25 8L13 13m5-9l1.75-1.75M20 6l1.75-1.75");
}

:global(.vy3vtac-a) {
  d: path("M3 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
