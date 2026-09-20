<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m1muscbxs"/><path class="rvoc0ob8r"/><path class="es-ot3p7v"/><path class="b--mi0m0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:iceberg-outline-bold" {...props}></Icon>
<style>
:global(.b--mi0m0m) {
  d: path("m8 12 6 6 6 -6");
}

:global(.es-ot3p7v) {
  d: path("M18 11h4");
}

:global(.m1muscbxs) {
  d: path("m6 11 6 -6 6 6Z");
}

:global(.rvoc0ob8r) {
  d: path("M2 11h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
