<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uiu_jkbcv"/><path class="kt47z8t9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:legal-hold-sharp" {...props}></Icon>
<style>
:global(.kt47z8t9q) {
  d: path("M14.25 2.75v5h5m-8.75 3.5v6.5m3-6.5v6.5");
}

:global(.uiu_jkbcv) {
  d: path("M6.75 2.75h7.5l5 5v13.5H4.75V2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
