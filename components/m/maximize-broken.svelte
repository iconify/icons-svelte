<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="talkkf4ro"/><path class="o35tmfo7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-broken" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o35tmfo7o) {
  d: path("M9 15L2 22M2 16.1429V22H7.85714");
}

:global(.talkkf4ro) {
  d: path("M22 7.85714V2H16.1429M22 2L18.5 5.5M15 9L15.875 8.125");
}

</style>
