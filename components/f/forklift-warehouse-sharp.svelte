<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jvw8rybug"/><path class="p0ly8bctm"/><path class="kdhdbbbdf"/><circle class="jul19qooo"/><circle class="c_j4n_qjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:forklift-warehouse-sharp" {...props}></Icon>
<style>
:global(.c_j4n_qjl) {
  cx: 10.25px;
  cy: 19.75px;
  r: 1.25px;
}

:global(.jul19qooo) {
  cx: 4.75px;
  cy: 19.75px;
  r: 1.25px;
}

:global(.jvw8rybug) {
  d: path("M2.75 14.5v-5H6V12h5.5v3.5H2.75z");
}

:global(.kdhdbbbdf) {
  d: path("M17.5 14.75h3.75v4.5H17.5z");
}

:global(.p0ly8bctm) {
  d: path("M4.25 9.5V4.75h6.25V12m1 1h3m0-9.5v15.75h6.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
