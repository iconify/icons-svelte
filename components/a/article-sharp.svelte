<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="i9mrqh3nn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:article-sharp" {...props}></Icon>
<style>
:global(.i9mrqh3nn) {
  d: path("M7 6.25h5v5H7zm8 1h2m-2 3h2m-10 4.5h10M7 18h6");
}

:global(.ohxdrbbbi) {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
