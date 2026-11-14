<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j5x4cro4e"/><path class="t-e85zbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-logger" {...props}></Icon>
<style>
:global(.j5x4cro4e) {
  d: path("M2.5 4h13v12h-13Zm13 6H17a2 2 0 0 1 2 2v3m-1.5 0h3v6.5h-3Z");
}

:global(.t-e85zbku) {
  d: path("M5.75 13H8.5v-3H11V7h1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
