<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eq_hyg60b"/><path class="fze4jkbok"/><path class="m6o3bac1v"/><path class="o062g1b0a"/><path class="o0ozwgb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prefilter-duotone-regular" {...props}></Icon>
<style>
:global(.eq_hyg60b) {
  fill: currentColor;
  d: path("M3 3h18l-7 7v5h-4v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fze4jkbok) {
  fill: currentColor;
  d: path("M12.5 17.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m6o3bac1v) {
  d: path("M3 3h18l-7 7v5h-4v-5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o062g1b0a) {
  d: path("M12.5 17.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.o0ozwgb-f) {
  d: path("m18 20 2 2");
}

</style>
