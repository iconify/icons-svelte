<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4a1ohbhq"/><path class="ce9vbeb8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:countdown-ten" {...props}></Icon>
<style>
:global(.ce9vbeb8o) {
  d: path("m7.5 11.5l1.5-1v6m2.75-3a2 3 0 1 0 4 0a2 3 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y4a1ohbhq) {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Zm6-11h4m-2 0v3");
}

</style>
