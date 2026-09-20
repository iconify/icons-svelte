<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="ijaucublj"/><path class="snz4b14xb"/><path class="skbifdbcx"/><path class="hxagq7byt"/><path class="v-cn4ub6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-branch-duotone-thin" {...props}></Icon>
<style>
:global(.ft030md1w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hxagq7byt) {
  d: path("M13 11v10");
}

:global(.ijaucublj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 11v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

:global(.snz4b14xb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 15 4 -4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v-cn4ub6a) {
  d: path("m13 15 4 -4h4");
}

</style>
