<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ao3p-fb6g"/><path class="ra_e5jb1j"/><circle class="kltucobhk"/><path class="sfz09sb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:encrypted-sharp" {...props}></Icon>
<style>
:global(.ao3p-fb6g) {
  d: path("M11.75 21.25h-7V2.75h9l5.5 5.5v3");
}

:global(.kltucobhk) {
  cx: 16px;
  cy: 18.75px;
  r: 2px;
}

:global(.ra_e5jb1j) {
  d: path("M13.75 2.75v5.5h5.5m-11 4h4m-4 3.75h2.5");
}

:global(.sfz09sb9c) {
  d: path("m17.5 17.25l3-3m-1.25 1.25l1.25 1.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
