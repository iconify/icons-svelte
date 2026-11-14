<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pny41bcag"/><path class="gzcnkccgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fragile-package" {...props}></Icon>
<style>
:global(.gzcnkccgj) {
  d: path("M12 8.5L10 12l3.5 3l-2.5 5.5");
}

:global(.pny41bcag) {
  d: path("M3 3.5h18v17H3Zm0 5h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
