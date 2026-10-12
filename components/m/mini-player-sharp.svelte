<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mnepmhb3d"/><path class="i0gym9b7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mini-player-sharp" {...props}></Icon>
<style>
:global(.i0gym9b7a) {
  d: path("m15.26 14.06l2.23 1.38l.51.31l-.51.31l-2.23 1.38l-.51.31v-4z");
}

:global(.mnepmhb3d) {
  d: path("m3.75 3.75l5 5m0-4v4h-4m6.5 2.5h10v9h-10z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
