<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ngd_4va2s"/><path class="k9wk1abnv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-u-turn-right-sharp" {...props}></Icon>
<style>
:global(.k9wk1abnv) {
  d: path("m16.25 11.5l3.5 3.5l-3.5 3.5");
}

:global(.ngd_4va2s) {
  d: path("M20.25 5.5h-11a4.75 4.75 0 0 0 0 9.5h10.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
