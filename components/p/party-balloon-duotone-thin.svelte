<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bppolvb1n"/><path class="emoq9e-ad"/><path class="c9x5rubht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:party-balloon-duotone-thin" {...props}></Icon>
<style>
:global(.bppolvb1n) {
  fill: currentColor;
  d: path("M12 4c3.5 0 6 2.5 6 6s-2.5 6 -6 6 -6 -2.5 -6 -6 2.5 -6 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.c9x5rubht) {
  d: path("M12 16c0 2 2 3 1 5");
}

:global(.emoq9e-ad) {
  d: path("M12 4c3.5 0 6 2.5 6 6s-2.5 6 -6 6 -6 -2.5 -6 -6 2.5 -6 6 -6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
