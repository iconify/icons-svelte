<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ujy0tybfh"/><path class="qmyg63bpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blast-furnace" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qmyg63bpk) {
  d: path("M10.5 21v-2a1.5 1.5 0 0 1 3 0v2");
}

:global(.ujy0tybfh) {
  d: path("m9 21l-1.5-8l2-7.5a2.5 2.5 0 0 1 5 0l2 7.5l-1.5 8Zm6-14h4.5v14M3 21h18");
}

</style>
