<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dd7ic93tf"/><path class="kvkpyc0wg"/><path class="t9ia5kx4y"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:floor-lamp-duotone-thin" {...props}></Icon>
<style>
:global(.dd7ic93tf) {
  fill: currentColor;
  d: path("m5 10 4 -4h6l4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kvkpyc0wg) {
  d: path("m5 10 4 -4h6l4 4Z");
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.t9ia5kx4y) {
  d: path("M12 10v10");
}

</style>
