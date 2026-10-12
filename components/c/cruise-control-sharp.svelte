<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yda0a_kfi"/><path class="mp1jjnbtm"/><circle class="hvgdv64iz"/><path class="aod8jqbni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cruise-control-sharp" {...props}></Icon>
<style>
:global(.aod8jqbni) {
  d: path("M13.24 11.76L15.5 9.5");
}

:global(.hvgdv64iz) {
  cx: 12px;
  cy: 13px;
  r: 1.75px;
}

:global(.mp1jjnbtm) {
  d: path("m18.25 11.5l1.5 1.5l1.5-1.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yda0a_kfi) {
  d: path("M6.52 18.48A7.75 7.75 0 1 1 19.75 13");
}

</style>
