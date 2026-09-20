<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7mb9vbwf"/><path class="x_6spmb5u"/><path class="cfwe2fbcx"/><path class="gaonsmbbz"/><path class="v3qgglbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:junction-outline-thin" {...props}></Icon>
<style>
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

:global(.v3qgglbcl) {
  d: path("M12 9.5v5");
}

:global(.x_6spmb5u) {
  d: path("M16 2v6h6");
}

</style>
