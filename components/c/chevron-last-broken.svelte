<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m_uf8kb5f"/><path class="z49mobc8s"/><path class="nqop7gbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-last-broken" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_uf8kb5f) {
  stroke-linejoin: round;
  d: path("M12 10.25L13.5 12L7.49997 19");
}

:global(.nqop7gbey) {
  d: path("M16.5 5L16.5 19.0004");
}

:global(.z49mobc8s) {
  d: path("M8.99997 6.75L7.49997 5");
}

</style>
