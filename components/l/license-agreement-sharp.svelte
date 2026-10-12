<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q69dqgorn"/><circle class="wk00ypvul"/><path class="bdhq7u78x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:license-agreement-sharp" {...props}></Icon>
<style>
:global(.bdhq7u78x) {
  d: path("M18.75 8v13m0-4.5h2m-2 3h2");
}

:global(.q69dqgorn) {
  d: path("M2.75 2.75h11.5v18.5H2.75zM6 7h5m-5 3.25h3.5M6 17h5");
}

:global(.wk00ypvul) {
  cx: 18.75px;
  cy: 6px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
