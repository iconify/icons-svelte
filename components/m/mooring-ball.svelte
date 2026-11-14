<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vbmirtbdo"/><path class="o8azt6xtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mooring-ball" {...props}></Icon>
<style>
:global(.o8azt6xtq) {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3 20q3-2.25 6 0t6 0t6 0M6.5 11.5h11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vbmirtbdo) {
  d: path("M6.5 11.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
