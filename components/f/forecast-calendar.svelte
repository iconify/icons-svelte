<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="heqqxc23u"/><path class="h2mivromn"/><path class="o2nhk1b1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:forecast-calendar" {...props}></Icon>
<style>
:global(.h2mivromn) {
  d: path("M11.25 12.25a2 2 0 1 0-1.5 2");
}

:global(.heqqxc23u) {
  d: path("M3 4.5h18v17H3Zm4.5-2v4m9-4v4");
}

:global(.o2nhk1b1z) {
  d: path("M9.75 17.75h5.5a1.5 1.5 0 0 0 0-3a2.75 2.75 0 0 0-5.5 0a1.5 1.5 0 0 0 0 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
