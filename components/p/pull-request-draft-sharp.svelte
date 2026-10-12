<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m0ydh5bsj"/><circle class="mtl-gzbxy"/><circle class="fk_szrbck"/><path class="yvwq_5b0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pull-request-draft-sharp" {...props}></Icon>
<style>
:global(.fk_szrbck) {
  cx: 17.25px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.m0ydh5bsj) {
  cx: 6.75px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.mtl-gzbxy) {
  cx: 6.75px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yvwq_5b0m) {
  d: path("M6.75 7.5v9m10.5-12.75v1m0 3.75V10m0 3.5v1");
}

</style>
