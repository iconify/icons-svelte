<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v0678_blx"/><path class="x4yi1rozh"/><path class="mj2w05jsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coverage-overlap" {...props}></Icon>
<style>
:global(.mj2w05jsa) {
  d: path("M14.75 15L16 9l1.25 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v0678_blx) {
  d: path("M3 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

:global(.x4yi1rozh) {
  d: path("M11 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm-4.25 3L8 9l1.25 6");
}

</style>
