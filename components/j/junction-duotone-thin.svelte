<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmnj_rj7a"/><path class="uakhv-9cy"/><path class="wh_0_1bjo"/><path class="bf72izbtx"/><path class="zwn3rtbhc"/><path class="o7mb9vbwf"/><path class="x_6spmb5u"/><path class="cfwe2fbcx"/><path class="gaonsmbbz"/><path class="v3qgglbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:junction-duotone-thin" {...props}></Icon>
<style>
:global(.bf72izbtx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 22v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cfwe2fbcx) {
  d: path("M8 22v-6H2");
}

:global(.gaonsmbbz) {
  d: path("M16 22v-6h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o7mb9vbwf) {
  d: path("M8 2v6H2");
}

:global(.uakhv-9cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 2v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v3qgglbcl) {
  d: path("M12 9.5v5");
}

:global(.wh_0_1bjo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 22v-6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x_6spmb5u) {
  d: path("M16 2v6h6");
}

:global(.zmnj_rj7a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 2v6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zwn3rtbhc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
