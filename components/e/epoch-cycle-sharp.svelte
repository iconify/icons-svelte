<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tsa_9enlo"/><path class="rjxgisbjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:epoch-cycle-sharp" {...props}></Icon>
<style>
:global(.rjxgisbjn) {
  d: path("m10.25 9.75l2-1.5v7.5");
}

:global(.tsa_9enlo) {
  d: path("M19.75 12a7.75 7.75 0 1 1-2.27-5.48m.27-3.77v4h-4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
