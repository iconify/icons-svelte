<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vys7yc-0j"/><path class="l6wh3u4fh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:portico-sharp" {...props}></Icon>
<style>
:global(.l6wh3u4fh) {
  d: path("M10.25 21.25v-5h3.5v5");
}

:global(.vys7yc-0j) {
  d: path("m4.94 10.59l6.62-6.18L12 4l.44.41l6.62 6.18l.44.41h-15zM2.75 11h18.5v10.25H2.75zM7 12.75v8.5m10-8.5v8.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
