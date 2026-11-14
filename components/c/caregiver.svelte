<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cm_22obkk"/><path class="fzzc5bb3d"/><path class="ru3npftgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:caregiver" {...props}></Icon>
<style>
:global(.cm_22obkk) {
  d: path("M10.712 20.5H2.5c0-4.5 3-7 6.5-7c1.445 0 2.804.426 3.903 1.243M5.25 7a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

:global(.fzzc5bb3d) {
  fill: currentColor;
  d: path("M16.786 6.445C16.127 5.873 15.25 4.937 15.25 4c0-.75.6-1.25 1.25-1.25c.4 0 .75.25 1 .5c.25-.25.6-.5 1-.5c.65 0 1.25.5 1.25 1.25c0 .988-.977 1.977-1.643 2.536");
}

:global(.ru3npftgg) {
  d: path("M13.5 21.5c0-3 1.75-5 4-5s4 2 4 5Zm1.25-9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
