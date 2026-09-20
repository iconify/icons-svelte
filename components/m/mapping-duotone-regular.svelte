<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w86l7qbyt"/><path class="bs0a9_brj"/><path class="mq8aagbsg"/><path class="o5-fqq0mw"/><path class="v8t4v3o4q"/><path class="qxpcblx0q"/><path class="xzn4jmbzj"/><path class="yw0xzbbmi"/><path class="n8h0kccut"/><path class="wl2374scp"/><path class="a04thmuhx"/><path class="o3p-ebloq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mapping-duotone-regular" {...props}></Icon>
<style>
:global(.a04thmuhx) {
  d: path("M8 12h7");
}

:global(.bs0a9_brj) {
  fill: currentColor;
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mq8aagbsg) {
  fill: currentColor;
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n8h0kccut) {
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o3p-ebloq) {
  d: path("M8 18h10");
}

:global(.o5-fqq0mw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qxpcblx0q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 18h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v8t4v3o4q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w86l7qbyt) {
  fill: currentColor;
  d: path("M4 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wl2374scp) {
  d: path("M8 6h10");
}

:global(.xzn4jmbzj) {
  d: path("M4 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yw0xzbbmi) {
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
