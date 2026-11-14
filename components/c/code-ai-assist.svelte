<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yzvwn0bpg"/><path class="fd-4a1omg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-ai-assist" {...props}></Icon>
<style>
:global(.fd-4a1omg) {
  d: path("M10 6.5L7.5 9l2.5 2.5m4-5L16.5 9L14 11.5m3.5 1.5q1 3.5 4.5 4.5q-3.5 1-4.5 4.5q-1-3.5-4.5-4.5q3.5-1 4.5-4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yzvwn0bpg) {
  d: path("M14.2 21.5H4.5v-19h15v9.7");
}

</style>
