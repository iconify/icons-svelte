<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qye9c0bkv"/><path class="bpo513kfk"/><path class="ti5-yebvj"/><path class="ilxguy6uu"/><path class="q3jyfybar"/><path class="k7llgzrde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-to-dot-duotone-thin" {...props}></Icon>
<style>
:global(.bpo513kfk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ilxguy6uu) {
  d: path("M12 4v10");
}

:global(.k7llgzrde) {
  d: path("M10 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.q3jyfybar) {
  d: path("m8 10 4 4 4 -4");
}

:global(.qye9c0bkv) {
  fill: currentColor;
  d: path("M10 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ti5-yebvj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 10 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
