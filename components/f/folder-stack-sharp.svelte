<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ttgrz1bqg"/><path class="dpv3wchbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:folder-stack-sharp" {...props}></Icon>
<style>
:global(.dpv3wchbo) {
  d: path("M2.75 9.25v-2h5.5l2 2h8v12H2.75v-2Z");
}

:global(.ttgrz1bqg) {
  d: path("M5.75 7.25v-4.5H11l2 2h8.25V18");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
