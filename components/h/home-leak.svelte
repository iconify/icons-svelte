<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o3xyavuxm"/><path class="k90jhcb0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:home-leak" {...props}></Icon>
<style>
:global(.k90jhcb0d) {
  d: path("M10.5 4h3v4h-3ZM17 15s-2.25 2.5-2.25 4a2.25 2.25 0 0 0 4.5 0c0-1.5-2.25-4-2.25-4Z");
}

:global(.o3xyavuxm) {
  d: path("M2.5 6H14a3 3 0 0 1 3 3v3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
