<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jnfxmc4-h"/><path class="hzi05wb1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:desk-mat-sharp" {...props}></Icon>
<style>
:global(.hzi05wb1h) {
  d: path("M13.25 8.25h5v7h-5zm2.5 0V11");
}

:global(.jnfxmc4-h) {
  d: path("M2.75 5.25h18.5v13.5H2.75zm3 5.25h5m-5 3h5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
