<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z_vrkxb-f"/><path class="z11l6u8dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:document-lock-sharp" {...props}></Icon>
<style>
:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z_vrkxb-f) {
  d: path("M11.75 21.25h-7V2.75h9l5.5 5.5v3.5");
}

:global(.z11l6u8dk) {
  d: path("M13.75 2.75v5.5h5.5m-11 4h4m2 4h6.5v5h-6.5zm1.5 0v-3h3.5v3");
}

</style>
