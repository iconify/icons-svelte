<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wuqr2acil"/><path class="hgef23b7m"/><path class="k30xijbti"/><path class="pw_ntac8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-right-left-line-duotone" {...props}></Icon>
<style>
:global(.hgef23b7m) {
  d: path("M6 9L9 12L3 18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k30xijbti) {
  d: path("M21 18L15 12L21 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.pw_ntac8e) {
  d: path("M18 9L15 12L21 18");
}

:global(.wuqr2acil) {
  d: path("M3 18L9 12L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
