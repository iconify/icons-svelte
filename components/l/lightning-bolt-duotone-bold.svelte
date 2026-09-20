<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ct7pn2pfd"/><path class="o4ckmk68a"/><path class="mpli3ebdu"/><path class="mbgtdkbsk"/><path class="flblq5ico"/><path class="zsil77j-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lightning-bolt-duotone-bold" {...props}></Icon>
<style>
:global(.ct7pn2pfd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 2 -8 8h5l-8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.flblq5ico) {
  d: path("m13 14 6 6");
}

:global(.mbgtdkbsk) {
  d: path("m16 2 -8 8h5l-8 8");
}

:global(.mpli3ebdu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 14 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o4ckmk68a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zsil77j-s) {
  d: path("m19 14 -6 6");
}

</style>
