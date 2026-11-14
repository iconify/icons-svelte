<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tkao8rj2l"/><path class="strti_brb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:business-idea" {...props}></Icon>
<style>
:global(.strti_brb) {
  d: path("M11 9h3v3Z");
}

:global(.tkao8rj2l) {
  d: path("M9 17.5c0-2-3.5-3.5-3.5-7.5a6.5 6.5 0 0 1 13 0c0 4-3.5 5.5-3.5 7.5Zm.5 3h5M10 13l4-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
