<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x3l7cj9iq"/><path class="nldbk4b3i"/><path class="ffs26fbkv"/><path class="mka94xbix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:action-database-outline-thin" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mka94xbix) {
  d: path("m9 19 3 3 3 -3");
}

:global(.nldbk4b3i) {
  d: path("M4 6a8 3 0 0 0 16 0");
}

:global(.x3l7cj9iq) {
  d: path("M4 6a8 3 0 0 1 16 0v8a8 3 0 0 1 -16 0Z");
}

</style>
