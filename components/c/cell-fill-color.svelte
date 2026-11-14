<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ku6gglbim"/><path class="godzgjbiv"/><path class="d8me7sqvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cell-fill-color" {...props}></Icon>
<style>
:global(.d8me7sqvr) {
  d: path("M18 14c1.5 2 3 3.5 3 5a3 3 0 0 1-6 0c0-1.5 1.5-3 3-5Z");
}

:global(.godzgjbiv) {
  fill: currentColor;
  d: path("M13.8 15H9V9h6v4.3");
}

:global(.ku6gglbim) {
  d: path("M12.5 21H3V3h18v10.3M9 3v18m6-18v10.3M3 9h18M3 15h10.8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
