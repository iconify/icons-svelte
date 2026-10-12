<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mwe-9d8rn"/><circle class="hx-rxnbzw"/><circle class="m7thmobns"/><path class="cpuytsbrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:binary-tree-sharp" {...props}></Icon>
<style>
:global(.cpuytsbrt) {
  d: path("m11.28 7.37l-3.56 9.26m5-9.26l3.56 9.26");
}

:global(.hx-rxnbzw) {
  cx: 7px;
  cy: 18.5px;
  r: 2px;
}

:global(.m7thmobns) {
  cx: 17px;
  cy: 18.5px;
  r: 2px;
}

:global(.mwe-9d8rn) {
  cx: 12px;
  cy: 5.5px;
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
