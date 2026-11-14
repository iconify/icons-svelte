<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rh4hqugip"/><path class="vdo1j_06c"/><path class="k_7ap9b-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mine-fan" {...props}></Icon>
<style>
:global(.k_7ap9b-g) {
  d: path("M12 10.25L9 6.5l2.5-1.75l3.75 1Zm1.516 2.625l4.747-.723l.266 3.04l-2.741 2.748Zm-3.032 0l-1.747 4.473l-2.766-1.29l-1.009-3.748Z");
}

:global(.rh4hqugip) {
  d: path("M2 12a10 10 0 1 0 20 0a10 10 0 1 0-20 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vdo1j_06c) {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
