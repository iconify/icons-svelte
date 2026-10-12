<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="l6ygoqbfm"/><path class="x0bdf1jrb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:back-pain-sharp" {...props}></Icon>
<style>
:global(.l6ygoqbfm) {
  cx: 7.75px;
  cy: 4.75px;
  r: 2px;
}

:global(.x0bdf1jrb) {
  d: path("m9.25 8.25l4.442.808l.808 4.442l-2.5 7.75m2.5-7.75l2.5 7.75m-7.5-12L7.75 14M19.5 5.25L17.25 8.5h3L18 11.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
