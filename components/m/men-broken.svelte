<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o6xw0cclu"/><path class="gv_ugy92l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:men-broken" {...props}></Icon>
<style>
:global(.gv_ugy92l) {
  stroke-linejoin: round;
  d: path("M15.6357 8.33427L21.9998 2M16.9998 2H21.9998V7");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o6xw0cclu) {
  d: path("M6 7.07026C7.17669 6.38958 8.54285 6 10 6C14.4183 6 18 9.58172 18 14C18 18.4183 14.4183 22 10 22C5.58172 22 2 18.4183 2 14C2 12.5429 2.38958 11.1767 3.07026 10");
}

</style>
