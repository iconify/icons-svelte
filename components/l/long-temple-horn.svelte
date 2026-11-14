<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cl2-2t2rm"/><path class="y7f1inb-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:long-temple-horn" {...props}></Icon>
<style>
:global(.cl2-2t2rm) {
  d: path("M4.5 20c3-1.5 5-4 5.5-7.5l1-8l-.75-2.5h3.5L13 4.5l1 8c.5 3.5 2.5 6 5.5 7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y7f1inb-x) {
  d: path("M4.5 20a7.5 1.5 0 1 0 15 0a7.5 1.5 0 1 0-15 0");
}

</style>
