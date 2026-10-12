<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ln5ecq_pj"/><circle class="ti2lvsb6o"/><path class="gyks0cbsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:prompt-send-sharp" {...props}></Icon>
<style>
:global(.gyks0cbsy) {
  d: path("M17.75 13.75V11m-1 1l1-1l1 1");
}

:global(.ln5ecq_pj) {
  d: path("M2.75 8h9v8h-9zm3.5 4h2");
}

:global(.ti2lvsb6o) {
  cx: 17.75px;
  cy: 12px;
  r: 3.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
