<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tema-wbby"/><path class="mgu0r2b4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:edge-ai-sharp" {...props}></Icon>
<style>
:global(.mgu0r2b4a) {
  d: path("m17.25 15l.27 1.98l1.98.27l-1.98.27l-.27 1.98l-.27-1.98l-1.98-.27l1.98-.27z");
}

:global(.tema-wbby) {
  d: path("M4.95 11.31a2.2 2.2 0 0 1-.3-4.38a3.16 3.16 0 0 1 5.86-.76a2.48 2.48 0 0 1-.33 5.14ZM8 13.75v3.5h3.75m1.5-4h8v8h-8z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
