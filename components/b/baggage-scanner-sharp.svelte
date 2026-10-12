<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lotfavbxd"/><path class="z2s01qsld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:baggage-scanner-sharp" {...props}></Icon>
<style>
:global(.lotfavbxd) {
  d: path("M5.75 15.25V4.75h12.5v10.5m-15.5 0h18.5m-17.5 3.5h16.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z2s01qsld) {
  d: path("M9 10.75h6v4.5H9zm1.75 0V8h2.5v2.75");
}

</style>
