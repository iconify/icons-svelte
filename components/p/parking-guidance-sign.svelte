<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1lvshbah"/><path class="ja5f5mwdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parking-guidance-sign" {...props}></Icon>
<style>
:global(.ja5f5mwdu) {
  d: path("M9 6h2.5a2 2 0 0 1 0 4H9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x1lvshbah) {
  d: path("M2.5 3h14l5 5.5l-5 5.5h-14ZM6 14v7.5M9 6v5.25");
}

</style>
