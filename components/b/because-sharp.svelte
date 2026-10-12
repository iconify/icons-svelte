<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vha_j0t2o"/><circle class="aewuuhb3v"/><circle class="qg0ecjuof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:because-sharp" {...props}></Icon>
<style>
:global(.aewuuhb3v) {
  cx: 18.5px;
  cy: 6.25px;
  r: 2.5px;
}

:global(.qg0ecjuof) {
  cx: 12px;
  cy: 18px;
  r: 2.5px;
}

:global(.vha_j0t2o) {
  cx: 5.5px;
  cy: 6.25px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
