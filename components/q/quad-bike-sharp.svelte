<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="feef-njgk"/><circle class="uqtm_0bwt"/><circle class="kpq69ek8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quad-bike-sharp" {...props}></Icon>
<style>
:global(.feef-njgk) {
  d: path("M2.75 13.75V12.5l.61-.44l1.53-1.12l.61-.44h13l.61.44l1.53 1.12l.61.44v2H2.75zM7.25 8h5.5v2.5h-5.5zm8.25 2.5l1-4h2");
}

:global(.kpq69ek8f) {
  cx: 18px;
  cy: 17.25px;
  r: 3px;
}

:global(.uqtm_0bwt) {
  cx: 6px;
  cy: 17.25px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
