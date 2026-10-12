<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mf-f1vb0k"/><circle class="z2o0ujiuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pinball-sharp" {...props}></Icon>
<style>
:global(.mf-f1vb0k) {
  d: path("m4.24 12.84l1.02-.18l.99-.16l.65.76l2.95 3.48l.65.76l-.5.63l-.5.62l-.89-.45l-3.72-1.85L4 16l-.24-.97l-.27-1.06l-.24-.97zm15.52 0l-1.02-.18l-.99-.16l-.65.76l-2.95 3.48l-.65.76l.5.63l.5.62l.89-.45l3.72-1.85L20 16l.24-.97l.27-1.06l.24-.97z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z2o0ujiuj) {
  cx: 12px;
  cy: 7px;
  r: 3px;
}

</style>
