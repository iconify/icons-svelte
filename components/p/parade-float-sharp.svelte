<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e_1b9vb-c"/><circle class="zanv7q--q"/><circle class="pjrb6zm3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parade-float-sharp" {...props}></Icon>
<style>
:global(.e_1b9vb-c) {
  d: path("m12.14 3.07l.69 1.53l.14.32l.35.03l1.66.18l.35.04l-.26.23l-1.24 1.13l-.26.23l.07.34l.35 1.64l.07.34l-.31-.17l-1.45-.84l-.3-.17l-.3.17l-1.45.84l-.31.17l.07-.34l.35-1.64l.07-.34l-.26-.23L8.93 5.4l-.26-.23l.35-.04l1.66-.18l.35-.03l.14-.32l.69-1.53l.14-.32zm-9.39 8.18h18.5v4.5H2.75z");
}

:global(.pjrb6zm3p) {
  cx: 17px;
  cy: 19.75px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zanv7q--q) {
  cx: 7px;
  cy: 19.75px;
  r: 1.5px;
}

</style>
