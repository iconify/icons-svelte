<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oh4p-ccfe"/><path class="bp7ccradc"/><path class="mc77_dknm"/><path class="ghtf55bhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:banner-dismiss-outline-thin" {...props}></Icon>
<style>
:global(.bp7ccradc) {
  d: path("M5 12h6");
}

:global(.ghtf55bhy) {
  d: path("m19 10 -4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mc77_dknm) {
  d: path("m15 10 4 4");
}

:global(.oh4p-ccfe) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
