<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8i06vb7h"/><path class="todsfdhkg"/><path class="kw9oa7xce"/><path class="cdily2n9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-down-duotone-thin" {...props}></Icon>
<style>
:global(.cdily2n9h) {
  d: path("m4 13 8 8 8 -8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kw9oa7xce) {
  d: path("m4 4 8 8 8 -8");
}

:global(.r8i06vb7h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 4 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.todsfdhkg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 13 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
