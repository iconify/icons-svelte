<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="x2d6451cz"/><path class="kolpghbpa"/><path class="yjvw8cn9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pocketcheck" {...props}></Icon>
<style>
:global(.kolpghbpa) {
  d: path("m14.88 26.467l4.436 4.435l13.803-13.804");
}

:global(.x2d6451cz) {
  d: path("M9.108 6.988h29.784c2.276 0 4.108 1.57 4.108 3.52V30.9c0 13.482-38 13.482-38 0V10.507c0-1.95 1.832-3.52 4.108-3.52Z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yjvw8cn9s) {
  stroke-dasharray: 3 3;
  d: path("M7.614 14.176v17.807l3.964 4.308M40.32 14.176v17.807l-3.963 4.308");
}

</style>
