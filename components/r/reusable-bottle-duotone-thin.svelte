<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6oxtkb2a"/><path class="le629bcat"/><path class="n953y9b3y"/><path class="l0v-b4kbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reusable-bottle-duotone-thin" {...props}></Icon>
<style>
:global(.f6oxtkb2a) {
  fill: currentColor;
  d: path("M8 7v14h8V7Z");
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

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.le629bcat) {
  d: path("M8 7v14h8V7Z");
}

:global(.n953y9b3y) {
  d: path("M10 7V3h4v4");
}

</style>
