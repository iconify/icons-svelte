<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l_yqoccsh"/><path class="goxf-3b_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pomegranate-juice" {...props}></Icon>
<style>
:global(.goxf-3b_m) {
  d: path("M16.75 15.75V14L18 15l1.25-1v1.75");
}

:global(.l_yqoccsh) {
  d: path("M3 2.5h9.5l-1 19H4ZM3.25 6h9M15 18.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
