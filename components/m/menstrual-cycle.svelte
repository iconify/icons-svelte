<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jw73fgbpu"/><path class="rno_0wblq"/><path class="rfthxzl-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:menstrual-cycle" {...props}></Icon>
<style>
:global(.jw73fgbpu) {
  d: path("M16.982 7.563a7.75 7.75 0 1 1-9.964 0");
}

:global(.rfthxzl-h) {
  fill: currentColor;
  d: path("M12 2.25C13.5 4 14.25 5 14.25 6c0 1.25-1 2.25-2.25 2.25S9.75 7.25 9.75 6c0-1 .75-2 2.25-3.75Z");
}

:global(.rno_0wblq) {
  d: path("M5.5 6.5L7 8l2.25-.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
