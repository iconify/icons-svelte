<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kgoxgjbrq"/><path class="n582-rtxx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:invitation-card-sharp" {...props}></Icon>
<style>
:global(.kgoxgjbrq) {
  d: path("M6 10V2.75h12V10Zm-3.25 0h18.5v11.25H2.75z");
}

:global(.n582-rtxx) {
  d: path("M2.75 11L12 16.75L21.25 11");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
