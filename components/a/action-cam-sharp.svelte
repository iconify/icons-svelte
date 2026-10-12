<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dbj-8dbfb"/><circle class="tubvt93bf"/><path class="ai917_bhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:action-cam-sharp" {...props}></Icon>
<style>
:global(.ai917_bhn) {
  d: path("M5.75 9.25h3");
}

:global(.dbj-8dbfb) {
  d: path("M5.5 5.75v-2h3.75v2h12v13.5H2.75V5.75z");
}

:global(.tubvt93bf) {
  cx: 14.5px;
  cy: 12.5px;
  r: 4px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
