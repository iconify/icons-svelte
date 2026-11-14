<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7g0ct9xi"/><path class="z0pnk883i"/><path class="dmpb6dl5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:compass-drafting-circle" {...props}></Icon>
<style>
:global(.dmpb6dl5m) {
  d: path("M3.75 17.5a14.5 14.5 0 0 0 16.5 0");
}

:global(.t7g0ct9xi) {
  d: path("M10.5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z0pnk883i) {
  d: path("M6.5 19L12 6l5.5 13");
}

</style>
