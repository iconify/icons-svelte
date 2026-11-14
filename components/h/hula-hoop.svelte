<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hj-k73b8q"/><path class="m_67pxbjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hula-hoop" {...props}></Icon>
<style>
:global(.hj-k73b8q) {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 3.5v7M9 21l3-6.5l3 6.5");
}

:global(.m_67pxbjq) {
  d: path("m8 6l4 3l4-3M3.5 13a8.5 2.5 0 1 0 17 0a8.5 2.5 0 1 0-17 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
