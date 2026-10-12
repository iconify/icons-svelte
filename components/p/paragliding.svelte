<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z6l5k_bry"/><circle class="rip_g9cqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:paragliding" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rip_g9cqu) {
  cx: 12px;
  cy: 19.25px;
  r: 2px;
}

:global(.z6l5k_bry) {
  d: path("M2.75 9.5c2-4.5 5.5-6.75 9.25-6.75S19.25 5 21.25 9.5C18.75 8 15.5 7.25 12 7.25S5.25 8 2.75 9.5m1 0L12 17m8.25-7.5L12 17");
}

</style>
