<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gwlgtkb9v"/><path class="ebqzi9bwo"/><path class="webna2bbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:double-exposure" {...props}></Icon>
<style>
:global(.ebqzi9bwo) {
  d: path("M8.5 8.5h13v13h-13Z");
}

:global(.gwlgtkb9v) {
  d: path("M2.5 2.5h13v13h-13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.webna2bbr) {
  d: path("m13.5 21.5l4-4l4 4");
}

</style>
