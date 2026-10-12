<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="ormgmjbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-transfer-sharp" {...props}></Icon>
<style>
:global(.ormgmjbpi) {
  d: path("M13.75 2.75v5.5h5.5m-10.75 4h6.75m-2-1.75l2 1.75l-2 1.75m2.25 2.5H8.75m2-1.75l-2 1.75l2 1.75");
}

:global(.rh2140hgr) {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
