<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tv_h2ebsi"/><path class="ld8ympnzk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:message-sticker-sharp" {...props}></Icon>
<style>
:global(.ld8ympnzk) {
  d: path("M15.25 4.25V9.5h5.25m-13 2.75l3.25 2.786L14 12.25");
}

:global(.tv_h2ebsi) {
  d: path("M2.75 6.25v-2.5H14.7l.621.001l.439.439l5.05 5.05l.439.439l.001.621V18H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
