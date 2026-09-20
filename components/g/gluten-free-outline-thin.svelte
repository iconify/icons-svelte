<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7xk8o29f"/><path class="v4iyegbro"/><path class="xhssufbfj"/><path class="bydm5bjkj"/><path class="c3g7d7t3t"/><path class="emvotkb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gluten-free-outline-thin" {...props}></Icon>
<style>
:global(.bydm5bjkj) {
  d: path("m12 14 -4 -4");
}

:global(.c3g7d7t3t) {
  d: path("m12 14 4 -4");
}

:global(.emvotkb4z) {
  d: path("M4 20 20 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.v4iyegbro) {
  d: path("M12 9 8 5");
}

:global(.xhssufbfj) {
  d: path("m12 9 4 -4");
}

</style>
