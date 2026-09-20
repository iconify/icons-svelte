<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldl0azwpx"/><path class="zca9n5m2v"/><path class="s9miuis1i"/><path class="y92rdcc_s"/><path class="h7bcztycq"/><path class="zdy8cdcdt"/><path class="gnvc2jbpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:indoor-plant-duotone-thin" {...props}></Icon>
<style>
:global(.gnvc2jbpq) {
  d: path("M12 10c3 0 5 -2 5 -5 -3 0 -5 2 -5 5");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldl0azwpx) {
  fill: currentColor;
  d: path("M9 16v5h6v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s9miuis1i) {
  fill: currentColor;
  d: path("M12 10c3 0 5 -2 5 -5 -3 0 -5 2 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y92rdcc_s) {
  d: path("M9 16v5h6v-5Z");
}

:global(.zca9n5m2v) {
  fill: currentColor;
  d: path("M12 12c-3 0 -5 -2 -5 -5 3 0 5 2 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zdy8cdcdt) {
  d: path("M12 12c-3 0 -5 -2 -5 -5 3 0 5 2 5 5");
}

</style>
