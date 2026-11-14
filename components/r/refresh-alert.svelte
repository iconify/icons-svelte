<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sxtlwx92v"/><path class="el34zpb9u"/><path class="m3c9gbb4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:refresh-alert" {...props}></Icon>
<style>
:global(.el34zpb9u) {
  d: path("m15.5 9l3 3l3-3m-3.871 6.25A6.5 6.5 0 0 1 5.5 12");
}

:global(.m3c9gbb4g) {
  d: path("m2.5 15l3-3l3 3M12 9v3.25M12 15h.01");
}

:global(.sxtlwx92v) {
  d: path("M6.371 8.75A6.5 6.5 0 0 1 18.5 12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
