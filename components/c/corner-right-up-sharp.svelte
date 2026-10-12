<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eol9p-bzi"/><path class="g8-uwvbdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:corner-right-up-sharp" {...props}></Icon>
<style>
:global(.eol9p-bzi) {
  d: path("M4.25 19.75h10.5v-15");
}

:global(.g8-uwvbdc) {
  d: path("m11 8.5l3.75-3.75L18.5 8.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
