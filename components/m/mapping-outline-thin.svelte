<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzn4jmbzj"/><path class="yw0xzbbmi"/><path class="n8h0kccut"/><path class="wl2374scp"/><path class="a04thmuhx"/><path class="o3p-ebloq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mapping-outline-thin" {...props}></Icon>
<style>
:global(.a04thmuhx) {
  d: path("M8 12h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n8h0kccut) {
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.o3p-ebloq) {
  d: path("M8 18h10");
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
