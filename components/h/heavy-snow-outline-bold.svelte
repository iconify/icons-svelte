<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c-pcdbceg"/><path class="kafgvtbap"/><path class="peew4rbrn"/><path class="r7ao24n4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heavy-snow-outline-bold" {...props}></Icon>
<style>
:global(.c-pcdbceg) {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.kafgvtbap) {
  d: path("M7 15.5v5m-2.5 0 5 -5");
}

:global(.peew4rbrn) {
  d: path("M17 15.5v5m-2.5 0 5 -5");
}

:global(.r7ao24n4h) {
  d: path("M4 22h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
