<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kosxb-loy"/><path class="dqi3mwb8t"/><path class="r150lzz5g"/><path class="skbifdbcx"/><path class="hxagq7byt"/><path class="v-cn4ub6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-branch-duotone-regular" {...props}></Icon>
<style>
:global(.dqi3mwb8t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 11v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hxagq7byt) {
  d: path("M13 11v10");
}

:global(.kosxb-loy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r150lzz5g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 15 4 -4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

:global(.v-cn4ub6a) {
  d: path("m13 15 4 -4h4");
}

</style>
