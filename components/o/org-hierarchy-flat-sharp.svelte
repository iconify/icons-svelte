<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><path class="z1w56pb_d"/><circle class="u978tybzz"/><circle class="tyhetpb4e"/><circle class="uxmu2ccyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:org-hierarchy-flat-sharp" {...props}></Icon>
<style>
:global(.tyhetpb4e) {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.u978tybzz) {
  cx: 5px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.uxmu2ccyb) {
  cx: 19px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.wv5f_1brg) {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z1w56pb_d) {
  d: path("M12 7.75v8.75m-7 0V11h14v5.5");
}

</style>
