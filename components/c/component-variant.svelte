<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezfuhbbdz"/><path class="ytbsx7b5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:component-variant" {...props}></Icon>
<style>
:global(.ezfuhbbdz) {
  d: path("m12 2.5l9.5 9.5l-9.5 9.5L2.5 12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytbsx7b5w) {
  d: path("m12 8.5l3.5 3.5l-3.5 3.5L8.5 12Z");
}

</style>
