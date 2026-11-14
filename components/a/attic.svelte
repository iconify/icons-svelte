<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vilsfcbox"/><path class="y_evnvbxu"/><path class="ixv163bsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:attic" {...props}></Icon>
<style>
:global(.ixv163bsh) {
  d: path("M10 21v-4h4v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vilsfcbox) {
  fill: currentColor;
  d: path("m3.5 10.5l8.5-7l8.5 7Z");
}

:global(.y_evnvbxu) {
  d: path("M3.5 10.5V21h17V10.5");
}

</style>
