<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f_ac1f42b"/><path class="lgpakg6ky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:knot-sailor-sharp" {...props}></Icon>
<style>
:global(.f_ac1f42b) {
  d: path("M2.75 14.5h6.5v-8a2.75 2.75 0 0 1 5.5 0V14h1.5m2.5 0h2.5");
}

:global(.lgpakg6ky) {
  d: path("M2.75 7.5H6.5V13m.37 3a5.5 5.5 0 0 0 10.63-2V8h3.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
