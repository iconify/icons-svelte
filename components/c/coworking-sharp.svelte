<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="qu3-hqbsn"/><circle class="s2aba_b7h"/><path class="qptsx1byb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coworking-sharp" {...props}></Icon>
<style>
:global(.qptsx1byb) {
  d: path("M4.25 9.5h6V15h-6zm9.5 0h6V15h-6zm-11 5.5h18.5m-16 0v6.25M18.75 15v6.25");
}

:global(.qu3-hqbsn) {
  cx: 7.25px;
  cy: 4.75px;
  r: 1.75px;
}

:global(.s2aba_b7h) {
  cx: 16.75px;
  cy: 4.75px;
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
