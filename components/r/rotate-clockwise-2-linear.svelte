<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="no67m_b_b"/><path class="f4uzock3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rotate-clockwise-2-linear" {...props}></Icon>
<style>
:global(.f4uzock3w) {
  d: path("M13.0711 14.929C11.6904 13.548 11 12.858 11 12C11 11.142 11.6904 10.452 13.0711 9.071C14.4518 7.69 15.1421 7 16 7C16.8579 7 17.5482 7.69 18.9289 9.071C20.3096 10.452 21 11.142 21 12C21 12.858 20.3096 13.548 18.9289 14.929C17.5482 16.31 16.8579 17 16 17C15.1421 17 14.4518 16.31 13.0711 14.929Z");
}

:global(.jx0p4fbya) {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.no67m_b_b) {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 7.429V4H4.25M8 4C4.875 6.857 3 9 3 12C3 15 4.7524 18.286 8 20");
}

</style>
