<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qps69pb2b"/><path class="b0s038b9v"/><path class="x6wxoo4ws"/><path class="lp2ig7bjb"/><path class="o46_3ibvz"/><path class="gzh4n16ws"/><path class="b6ubinbne"/><path class="ti0atfbnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:robot-arm-duotone-thin" {...props}></Icon>
<style>
:global(.b0s038b9v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b6ubinbne) {
  d: path("m6 12 6 -6h8v3.5");
}

:global(.gzh4n16ws) {
  d: path("M6 12v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lp2ig7bjb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 6v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o46_3ibvz) {
  d: path("M3 20h6");
}

:global(.qps69pb2b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ti0atfbnf) {
  d: path("M17 6v3.5");
}

:global(.x6wxoo4ws) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 12 6 -6h8v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
