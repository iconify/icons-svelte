<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="t6ozvr6zj"/><circle class="z1qpurb8m"/><path class="qnrk4qblw"/><circle class="yjztigbem"/><path class="bq857wblc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:family-sharp" {...props}></Icon>
<style>
:global(.bq857wblc) {
  d: path("M10.75 20.5v-3h2.5v3");
}

:global(.qnrk4qblw) {
  d: path("M2.75 20.5V17a2.5 2.5 0 0 1 5 0v3.5m8.5 0V17a2.5 2.5 0 0 1 5 0v3.5");
}

:global(.t6ozvr6zj) {
  cx: 5.25px;
  cy: 9px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yjztigbem) {
  cx: 12px;
  cy: 12.5px;
  r: 2px;
}

:global(.z1qpurb8m) {
  cx: 18.75px;
  cy: 9px;
  r: 2.5px;
}

</style>
