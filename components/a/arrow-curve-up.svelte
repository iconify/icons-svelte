<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o7qzh_bmi"/><path class="re-k1ub6p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-curve-up" {...props}></Icon>
<style>
:global(.o7qzh_bmi) {
  d: path("M4 18.5c7.5 0 12-5 12-13.5");
}

:global(.re-k1ub6p) {
  d: path("M12.5 8.5L16 5l3.5 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
