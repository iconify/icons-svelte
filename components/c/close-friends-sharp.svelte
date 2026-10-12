<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ilmx_fbfh"/><path class="kwbnkab4e"/><circle class="szz5nabpn"/><path class="jevjsnbuh"/><path class="y8-q1fbwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:close-friends-sharp" {...props}></Icon>
<style>
:global(.ilmx_fbfh) {
  cx: 6.5px;
  cy: 7.5px;
  r: 2.75px;
}

:global(.jevjsnbuh) {
  d: path("M14.25 20.25h7V17a3.75 3.75 0 0 0-7.5 0v3.25z");
}

:global(.kwbnkab4e) {
  d: path("M3.25 20.25h7V17a3.75 3.75 0 0 0-7.5 0v3.25z");
}

:global(.szz5nabpn) {
  cx: 17.5px;
  cy: 7.5px;
  r: 2.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y8-q1fbwc) {
  d: path("m12.14 11.32l.75 1.69l.14.32l.35.03l1.84.19l.35.04l-.26.24l-1.38 1.23l-.26.23l.08.35l.38 1.8l.07.34l-.3-.17l-1.6-.92l-.3-.18l-.3.18l-1.6.92l-.3.17l.07-.34l.38-1.8l.08-.35l-.26-.23l-1.38-1.23l-.26-.24l.35-.04l1.84-.19l.35-.03l.14-.32l.75-1.69L12 11z");
}

</style>
