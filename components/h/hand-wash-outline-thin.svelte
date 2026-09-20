<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="znimqt98n"/><path class="mqbr2yyal"/><path class="ehnvkinxp"/><path class="i2-ny_bzf"/><path class="rsinobb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hand-wash-outline-thin" {...props}></Icon>
<style>
:global(.ehnvkinxp) {
  d: path("M7 4v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.mqbr2yyal) {
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
}

:global(.rsinobb0c) {
  d: path("M17 4v4");
}

:global(.znimqt98n) {
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
}

</style>
