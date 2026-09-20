<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pldekmw0i"/><path class="mbfwr1vcs"/><path class="t-3b9ybzs"/><path class="pb1wrt76j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deforestation-duotone-regular" {...props}></Icon>
<style>
:global(.mbfwr1vcs) {
  d: path("M5 19v-5h6v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pb1wrt76j) {
  d: path("M15 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pldekmw0i) {
  fill: currentColor;
  d: path("M15 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t-3b9ybzs) {
  d: path("m12 18 6 -6");
}

</style>
