<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sdgafkcgw"/><path class="lgr612izs"/><path class="oconzlhzu"/><path class="h5gy-ctti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:goal-missed-outline-thin" {...props}></Icon>
<style>
:global(.h5gy-ctti) {
  d: path("m22 9.5 -5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lgr612izs) {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.oconzlhzu) {
  d: path("m17 9.5 5 5");
}

:global(.sdgafkcgw) {
  d: path("M4 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
