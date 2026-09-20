<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lu0ovacdk"/><path class="oq9ztqbxu"/><path class="fglxyivky"/><path class="lx3jidcux"/><path class="k-jt90-vx"/><path class="tr__z6b9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:point-cloud-outline-thin" {...props}></Icon>
<style>
:global(.fglxyivky) {
  d: path("M18 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-jt90-vx) {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.lu0ovacdk) {
  d: path("M4 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.lx3jidcux) {
  d: path("M4 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.oq9ztqbxu) {
  d: path("M11 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.tr__z6b9j) {
  d: path("M18 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
