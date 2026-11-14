<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l1tv0xafw"/><path class="yntwclbqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:health-app" {...props}></Icon>
<style>
:global(.l1tv0xafw) {
  d: path("M6 2.5h12v19H6ZM10.5 5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yntwclbqx) {
  d: path("M8.5 13H10l1-2.5l1.75 5l1-2.5h1.75m-5 6h3");
}

</style>
