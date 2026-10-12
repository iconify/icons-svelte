<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n0r_n9bap"/><circle class="f--yjl04t"/><path class="kocvjibha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:projector-screen-sharp" {...props}></Icon>
<style>
:global(.f--yjl04t) {
  cx: 15.75px;
  cy: 12.25px;
  r: 2.75px;
}

:global(.kocvjibha) {
  d: path("M6.25 10.75h3.5m-3.5 3h3.5m-3.25 4v2.5m11-2.5v2.5");
}

:global(.n0r_n9bap) {
  d: path("M2.75 6.75h18.5v11H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
