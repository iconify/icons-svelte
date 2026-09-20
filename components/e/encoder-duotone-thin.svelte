<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixcncacmy"/><path class="p-hshlbhd"/><path class="bwuo0ywji"/><path class="ps3-67b_v"/><path class="wlia6bb5b"/><path class="adiugjbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:encoder-duotone-thin" {...props}></Icon>
<style>
:global(.adiugjbhs) {
  d: path("m15 9 3 3 -3 3");
}

:global(.bwuo0ywji) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixcncacmy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 3 6 6v6l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p-hshlbhd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ps3-67b_v) {
  d: path("m4 3 6 6v6l-6 6");
}

:global(.wlia6bb5b) {
  d: path("M11 12h7");
}

</style>
