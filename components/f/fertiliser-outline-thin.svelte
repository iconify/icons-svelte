<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t2m3fqb7m"/><path class="iu91ib-mt"/><path class="p-3tqnbzb"/><path class="o7w846b2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fertiliser-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu91ib-mt) {
  d: path("m6 8 3 -3h6l3 3");
}

:global(.o7w846b2d) {
  d: path("M13 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p-3tqnbzb) {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.t2m3fqb7m) {
  d: path("M6 21V8h12v13Z");
}

</style>
