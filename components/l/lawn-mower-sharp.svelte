<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="babiizbmu"/><circle class="m_ubk9bxa"/><circle class="vk0oucc3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lawn-mower-sharp" {...props}></Icon>
<style>
:global(.babiizbmu) {
  d: path("m8 11.75l-3.25-8.5H3m1.25 13v-4.5h15v4.5Z");
}

:global(.m_ubk9bxa) {
  cx: 7px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.vk0oucc3w) {
  cx: 16.75px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
