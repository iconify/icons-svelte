<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="z-ze1jbyb"/><path class="k_vj6sb3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:podcast-episode-sharp" {...props}></Icon>
<style>
:global(.k_vj6sb3c) {
  d: path("M8.82 5.82L5.644 9l3.176 3.18m6.36-6.36L18.356 9l-3.176 3.18M6.7 3.7a7.5 7.5 0 0 0 0 10.6M17.3 3.7a7.5 7.5 0 0 1 0 10.6M6 17.75h12M8.5 21h7");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z-ze1jbyb) {
  cx: 12px;
  cy: 9px;
  r: 1.5px;
}

</style>
