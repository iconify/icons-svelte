<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1mhbbbek"/><path class="g_sn6dbji"/><path class="oxrxwybca"/><path class="bg96ko_da"/><path class="z9p0k9q-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:qos-outline-thin" {...props}></Icon>
<style>
:global(.bg96ko_da) {
  d: path("m18 6 3 3 -3 3");
}

:global(.g_sn6dbji) {
  d: path("M2 12a2.5 2.5 0 0 1 2.5 -2.5h4A2.5 2.5 0 0 1 11 12a2.5 2.5 0 0 1 -2.5 2.5h-4A2.5 2.5 0 0 1 2 12");
}

:global(.h1mhbbbek) {
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h8A2.5 2.5 0 0 1 15 4.5 2.5 2.5 0 0 1 12.5 7h-8A2.5 2.5 0 0 1 2 4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oxrxwybca) {
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h3a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 7.5 22h-3A2.5 2.5 0 0 1 2 19.5");
}

:global(.z9p0k9q-r) {
  d: path("M21 9v9");
}

</style>
