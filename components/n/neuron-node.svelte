<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="ci5xfvneo"/><path class="h3qkj9bop"/><path class="g-e7vw6cu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:neuron-node" {...props}></Icon>
<style>
:global(.ci5xfvneo) {
  cx: 10px;
  cy: 12px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.g-e7vw6cu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 9L4.5 6m0 0V3.25M4.5 6H2.75M6 12H2.75m4.65 3l-2.9 3m0 0v2.75m0-2.75H2.75M14 12h4.5m0 0L21 9m-2.5 3l2.5 3");
}

:global(.h3qkj9bop) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
