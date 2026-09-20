<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bx5f_866s"/><path class="py9xm9zor"/><path class="m7_xl321u"/><path class="n7jp03moa"/><path class="gp7a30zvr"/><path class="o7mb9vbwf"/><path class="x_6spmb5u"/><path class="cfwe2fbcx"/><path class="gaonsmbbz"/><path class="v3qgglbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:junction-duotone-bold" {...props}></Icon>
<style>
:global(.bx5f_866s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 2v6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cfwe2fbcx) {
  d: path("M8 22v-6H2");
}

:global(.gaonsmbbz) {
  d: path("M16 22v-6h6");
}

:global(.gp7a30zvr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m7_xl321u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 22v-6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n7jp03moa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 22v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o7mb9vbwf) {
  d: path("M8 2v6H2");
}

:global(.py9xm9zor) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 2v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v3qgglbcl) {
  d: path("M12 9.5v5");
}

:global(.x_6spmb5u) {
  d: path("M16 2v6h6");
}

</style>
