<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cv5hscb1z"/><path class="e-jr8acgi"/><path class="a_h6p1b2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:photo-gallery-property" {...props}></Icon>
<style>
:global(.a_h6p1b2f) {
  d: path("m6 14.5l4.5-4l4.5 4v4H6v-4");
}

:global(.cv5hscb1z) {
  d: path("M2.5 7h16v14.5h-16Z");
}

:global(.e-jr8acgi) {
  d: path("M5.5 7V5.5A1.5 1.5 0 0 1 7 4h13a1.5 1.5 0 0 1 1.5 1.5v11A1.5 1.5 0 0 1 20 18h-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
