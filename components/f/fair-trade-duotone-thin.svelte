<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wj8ybccjk"/><path class="b7h8iyqlm"/><path class="ne413abhf"/><path class="fenqk1bqx"/><path class="drz60ab5x"/><path class="r7xk8o29f"/><path class="k4qo1xe9v"/><path class="bai-ikdbm"/><path class="qorafhbcl"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fair-trade-duotone-thin" {...props}></Icon>
<style>
:global(.b7h8iyqlm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bai-ikdbm) {
  d: path("M9 6a3 3 0 0 1 -6 0");
}

:global(.drz60ab5x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fenqk1bqx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k4qo1xe9v) {
  d: path("M4 6h16");
}

:global(.ne413abhf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qorafhbcl) {
  d: path("M21 6a3 3 0 0 1 -6 0");
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.wj8ybccjk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
