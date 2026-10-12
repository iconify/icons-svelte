<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="qi_z9gbzx"/><circle class="pf0l2ptyv"/><circle class="c4yce5bdg"/><path class="pf68-yb5h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:reasoning-steps-sharp" {...props}></Icon>
<style>
:global(.c4yce5bdg) {
  cx: 5.25px;
  cy: 19px;
  r: 1.75px;
}

:global(.pf0l2ptyv) {
  cx: 5.25px;
  cy: 12px;
  r: 1.75px;
}

:global(.pf68-yb5h) {
  d: path("M5.25 7.5v2m0 5v2M10 5h11.25M10 12h9m-9 7h6");
}

:global(.qi_z9gbzx) {
  cx: 5.25px;
  cy: 5px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
