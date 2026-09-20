<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydk-7sp0t"/><path class="iprvt7beg"/><path class="fijjj9b9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lip-sync-outline-thin" {...props}></Icon>
<style>
:global(.fijjj9b9u) {
  d: path("M20.54 6.46a5 5 0 0 1 0 7.08");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iprvt7beg) {
  d: path("M19.12 7.88a3 3 0 0 1 0 4.24");
}

:global(.ydk-7sp0t) {
  d: path("M14.5 10a5.5 5.5 0 0 1 -11 0");
}

</style>
