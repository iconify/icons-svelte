<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a_su9zb-k"/><path class="ivr40qt4r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:porridge-sharp" {...props}></Icon>
<style>
:global(.a_su9zb-k) {
  d: path("M3.75 11.5h16.5a8.25 6.75 0 0 1-16.5 0ZM9 21.25h6M14 8.5l3.5-5.75");
}

:global(.ivr40qt4r) {
  d: path("m8 14.25l2 1.385l2-1.385l2-1.385l2 1.385");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
