<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g00uv-b-x"/><path class="koh8ckbdb"/><path class="k2mg4f2ls"/><path class="j82qv6hym"/><path class="b7rizdb8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dropship-outline-regular" {...props}></Icon>
<style>
:global(.b7rizdb8r) {
  d: path("M9.5 8.5 12 11l-2.5 2.5");
}

:global(.g00uv-b-x) {
  d: path("M4 5h9a2 2 0 0 1 2 2v3h3.5l2.5 2.5V15a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2");
}

:global(.j82qv6hym) {
  d: path("M5.5 8.5 8 11l-2.5 2.5");
}

:global(.k2mg4f2ls) {
  d: path("M15 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.koh8ckbdb) {
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
