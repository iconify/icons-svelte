<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iw3vlhf6h"/><path class="lh950ufyw"/><path class="exhy59b7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:merchant-onboarding" {...props}></Icon>
<style>
:global(.exhy59b7w) {
  d: path("M8.5 20.5v-5h3.7M18 15v6m-3-3h6");
}

:global(.iw3vlhf6h) {
  d: path("m3 9l1.5-5h15L21 9a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 12 9a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 3 9Z");
}

:global(.lh950ufyw) {
  d: path("M5.25 11.25v9.25h6.95m6.55-8.35v-.9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
