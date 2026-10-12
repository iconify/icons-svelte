<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y_70syb0m"/><circle class="g0cbdgbgj"/><circle class="xv1gp_tin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coin-receive-sharp" {...props}></Icon>
<style>
:global(.g0cbdgbgj) {
  cx: 9.25px;
  cy: 14.75px;
  r: 6.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xv1gp_tin) {
  cx: 9.25px;
  cy: 14.75px;
  r: 3.25px;
}

:global(.y_70syb0m) {
  d: path("M9.25 5.75a6.5 6.5 0 1 1 9 9");
}

</style>
