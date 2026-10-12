<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ha2z4qbtg"/><circle class="c2vbuccni"/><path class="hdj66lbws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mri-scanner-sharp" {...props}></Icon>
<style>
:global(.c2vbuccni) {
  cx: 12px;
  cy: 10.5px;
  r: 3.5px;
}

:global(.ha2z4qbtg) {
  d: path("M2.75 3h18.5v15H2.75z");
}

:global(.hdj66lbws) {
  d: path("M6 21.25h12");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
