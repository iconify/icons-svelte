<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v54wlkm6z"/><path class="ywlkpyzgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:objection-handling" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v54wlkm6z) {
  d: path("M5 7h8a2.5 2.5 0 0 1 2.5 2.5V15a2.5 2.5 0 0 1-2.5 2.5H9l-4 3v-3A2.5 2.5 0 0 1 2.5 15V9.5A2.5 2.5 0 0 1 5 7");
}

:global(.ywlkpyzgy) {
  d: path("M9.75 3.25a2.5 2.5 0 0 1 1.75-.75H19A2.5 2.5 0 0 1 21.5 5v6a2.5 2.5 0 0 1-2.5 2.5h-.75M6 12.5l2 2l4-4");
}

</style>
