<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hdmnq7b-k"/><circle class="boiqtuypj"/><path class="stlv7x7mf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:contact-sheet-sharp" {...props}></Icon>
<style>
:global(.boiqtuypj) {
  cx: 15.75px;
  cy: 15.75px;
  r: 3.5px;
}

:global(.hdmnq7b-k) {
  d: path("M2.75 2.75h13v13h-13zm0 6.5h13m-6.5-6.5v13");
}

:global(.stlv7x7mf) {
  d: path("M18.25 18.25L21 21");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
