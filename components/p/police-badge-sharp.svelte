<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n31yb52ts"/><circle class="hjru5mbwv"/><circle class="ftdro6baa"/><circle class="jwub2_s5t"/><circle class="n2he7vj4w"/><circle class="rsnu82btf"/><circle class="s67nsxbky"/><circle class="peiq2hfxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:police-badge-sharp" {...props}></Icon>
<style>
:global(.ftdro6baa) {
  cx: 18.93px;
  cy: 8px;
  r: 1.25px;
}

:global(.hjru5mbwv) {
  cx: 12px;
  cy: 4px;
  r: 1.25px;
}

:global(.jwub2_s5t) {
  cx: 18.93px;
  cy: 16px;
  r: 1.25px;
}

:global(.n2he7vj4w) {
  cx: 12px;
  cy: 20px;
  r: 1.25px;
}

:global(.n31yb52ts) {
  d: path("m12.4 5.63l1.32 2.06l.41.63l.74.03l2.44.12l.75.03l-.34.67l-1.13 2.16l-.34.67l.34.67l1.13 2.16l.34.67l-.75.03l-2.44.12l-.74.03l-.41.63l-1.32 2.06l-.4.63l-.4-.63l-1.32-2.06l-.4-.63l-.75-.03l-2.44-.12l-.75-.03l.34-.67l1.13-2.16l.34-.67l-.34-.67l-1.13-2.16l-.34-.67l.75-.03l2.44-.12l.74-.03l.41-.63l1.32-2.06L12 5z");
}

:global(.peiq2hfxm) {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
}

:global(.rsnu82btf) {
  cx: 5.07px;
  cy: 16px;
  r: 1.25px;
}

:global(.s67nsxbky) {
  cx: 5.07px;
  cy: 8px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
