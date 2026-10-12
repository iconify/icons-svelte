<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="of5sgv6-m"/><path class="ukdxjsbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:policy-sharp" {...props}></Icon>
<style>
:global(.of5sgv6-m) {
  d: path("M10.5 21.25H4.75V2.75h9l5.5 5.5v2");
}

:global(.ukdxjsbya) {
  d: path("M13.75 2.75v5.5h5.5m-11 3.5h3.5M8.25 15h2M17 13.25l3.5 1.25V17c0 2.25-1.5 3.5-3.5 4.25c-2-.75-3.5-2-3.5-4.25v-2.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
