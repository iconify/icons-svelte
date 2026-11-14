<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eb3_pkztw"/><path class="gzrqh8b2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:landing-page-form" {...props}></Icon>
<style>
:global(.eb3_pkztw) {
  d: path("M2.5 4h19v16h-19Zm0 4h19");
}

:global(.gzrqh8b2n) {
  d: path("M6 11h12v3H6Zm2 6h8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
