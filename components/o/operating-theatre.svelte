<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xrv47me9p"/><path class="x1m36xanm"/><path class="hbdkgmb7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:operating-theatre" {...props}></Icon>
<style>
:global(.hbdkgmb7l) {
  d: path("M12 8v13.5M5.5 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x1m36xanm) {
  fill: currentColor;
  d: path("M7 2.5h10V6H7Z");
}

:global(.xrv47me9p) {
  d: path("M3 8h18v13.5H3Z");
}

</style>
