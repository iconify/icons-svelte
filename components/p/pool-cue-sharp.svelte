<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cg-y8ntbo"/><circle class="ybufkabpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pool-cue-sharp" {...props}></Icon>
<style>
:global(.cg-y8ntbo) {
  d: path("m3.64 18.36l5.47-5.47l.64-.64l.64.64l.72.72l.64.64l-.64.64l-5.47 5.47L5 21l-.64-.64l-.72-.72L3 19zm7.11-5.11l4.5-4.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybufkabpo) {
  cx: 18.5px;
  cy: 5.5px;
  r: 2.5px;
}

</style>
