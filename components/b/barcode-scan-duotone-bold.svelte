<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="vygzwktag"/><path class="cs9f_sbcc"/><path class="e2xrf551z"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jlpxneb5g"/><path class="h7bcztycq"/><path class="pqrd0wbvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barcode-scan-duotone-bold" {...props}></Icon>
<style>
:global(.c1kziyotx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cs9f_sbcc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.e2xrf551z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.hieqhxiaw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jlpxneb5g) {
  d: path("M9 8v8");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.pqrd0wbvk) {
  d: path("M15 8v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vygzwktag) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
