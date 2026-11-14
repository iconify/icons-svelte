<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sdrf9q9_y"/><path class="o9d4etjxg"/><path class="xazzummud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:amulet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o9d4etjxg) {
  d: path("M5.75 15.25a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0");
}

:global(.sdrf9q9_y) {
  d: path("M6 2.5C6 6 9 9 12 9s6-3 6-6.5");
}

:global(.xazzummud) {
  d: path("m13.145 13.353l.785.928a1.5 1.5 0 0 1 0 1.938l-.785.928a1.5 1.5 0 0 1-2.29 0l-.785-.928a1.5 1.5 0 0 1 0-1.938l.785-.928a1.5 1.5 0 0 1 2.29 0");
}

</style>
