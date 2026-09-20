<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g00uv-b-x"/><path class="koh8ckbdb"/><path class="k2mg4f2ls"/><path class="wz4-fdbkg"/><path class="cce1g4-ys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delivery-failed-outline-thin" {...props}></Icon>
<style>
:global(.cce1g4-ys) {
  d: path("m10.5 9 -4 4");
}

:global(.g00uv-b-x) {
  d: path("M4 5h9a2 2 0 0 1 2 2v3h3.5l2.5 2.5V15a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2mg4f2ls) {
  d: path("M15 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.koh8ckbdb) {
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wz4-fdbkg) {
  d: path("m6.5 9 4 4");
}

</style>
