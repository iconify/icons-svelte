<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mmhsavwfa"/><path class="ajjav7b8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:angle" {...props}></Icon>
<style>
:global(.ajjav7b8m) {
  d: path("M9.45 14.55a7 7 0 0 1 2.05 4.95");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mmhsavwfa) {
  d: path("m19 4.5l-14.5 15H20");
}

</style>
