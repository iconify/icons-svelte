<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="phf0y8b4e"/><path class="fzyb-ubtk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:metro-subway" {...props}></Icon>
<style>
:global(.fzyb-ubtk) {
  d: path("M8 7h8v4H8Zm0 10.5L6 21m10-3.5l2 3.5m-9.5-7h.01m6.99 0h.01");
}

:global(.phf0y8b4e) {
  d: path("M6 3.5h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-12a1 1 0 0 1 1-1Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
