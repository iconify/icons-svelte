<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kzvibbczt"/><path class="pzkkb1bdt"/><path class="ju63gachf"/><path class="ka5ob16ei"/><path class="sz1k7cmme"/><path class="z5jtjknvm"/><path class="nooweob_o"/><path class="u9z5qccfn"/><path class="qnebkmpov"/><path class="zbj6wacas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-warm-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ju63gachf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ka5ob16ei) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 8 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kzvibbczt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nooweob_o) {
  d: path("M3 10h12");
}

:global(.pzkkb1bdt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnebkmpov) {
  d: path("m18 8 2 -2 -2 -2");
}

:global(.sz1k7cmme) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 16 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u9z5qccfn) {
  d: path("M3 15h12");
}

:global(.z5jtjknvm) {
  d: path("M3 5h12");
}

:global(.zbj6wacas) {
  d: path("m18 16 2 -2 -2 -2");
}

</style>
