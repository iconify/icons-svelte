<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jon3jyusz"/><path class="x4nz41duv"/><path class="ob5egip6a"/><path class="u3or_dbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:charity-run-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jon3jyusz) {
  fill: currentColor;
  d: path("m3 9 5 -5h8l5 5 -4 4v7H7v-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ob5egip6a) {
  d: path("m11 11 2 -2v8");
}

:global(.u3or_dbos) {
  d: path("M11 17h4");
}

:global(.x4nz41duv) {
  d: path("m3 9 5 -5h8l5 5 -4 4v7H7v-7Z");
}

</style>
