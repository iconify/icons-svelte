<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fjf-4hw3z"/><path class="fpli-ik3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chocolate-bar-sharp" {...props}></Icon>
<style>
:global(.fjf-4hw3z) {
  d: path("M5 13V2.75h14V13l-1.75-1.25L15.5 13l-1.75-1.25L12 13l-1.75-1.25L8.5 13l-1.75-1.25Zm7-10.25V12M5 7.5h14");
}

:global(.fpli-ik3g) {
  d: path("m5 13l1.75-1.25L8.5 13l1.75-1.25L12 13l1.75-1.25L15.5 13l1.75-1.25L19 13v8.25H5v-2Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
