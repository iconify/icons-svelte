<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-fbcjv7k"/><path class="d34aqkbfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cadence" {...props}></Icon>
<style>
:global(.d34aqkbfk) {
  d: path("M11.5 9H15v3h-3.5Z");
}

:global(.r-fbcjv7k) {
  d: path("M8 3h8l4 18H4Zm4 14l2-10.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
