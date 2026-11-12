<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rxu47eqeo"/><path class="pkyac1btc"/><path class="d_1-t8bqs"/><path class="r4gkr88fv"/><path class="akly-1bxp"/><path class="vr5gl3zbo"/><path class="f1vdtsbwm"/><path class="u85h8qb3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-unordered-broken" {...props}></Icon>
<style>
:global(.akly-1bxp) {
  d: path("M5 6H5.0001");
}

:global(.d_1-t8bqs) {
  d: path("M10 14H21");
}

:global(.f1vdtsbwm) {
  d: path("M5 14H5.0001");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pkyac1btc) {
  d: path("M10 10H21");
}

:global(.r4gkr88fv) {
  d: path("M10 18H21");
}

:global(.rxu47eqeo) {
  d: path("M10 6H21");
}

:global(.u85h8qb3e) {
  d: path("M5 18H5.0001");
}

:global(.vr5gl3zbo) {
  d: path("M5 10H5.0001");
}

</style>
