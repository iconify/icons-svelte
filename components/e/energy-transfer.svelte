<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hk192lb1n"/><path class="m_l7hk9ss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:energy-transfer" {...props}></Icon>
<style>
:global(.hk192lb1n) {
  d: path("M2.5 12h7v7h-7Zm12 0h7v7h-7ZM6 9q6-8 12 0");
}

:global(.m_l7hk9ss) {
  d: path("M14.75 8.5L18 9l.5-3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
