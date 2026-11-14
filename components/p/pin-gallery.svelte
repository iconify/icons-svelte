<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abpufxbpi"/><path class="ezc_z5bls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-gallery" {...props}></Icon>
<style>
:global(.abpufxbpi) {
  d: path("M4.75 8h14.5A1.75 1.75 0 0 1 21 9.75v9.5A1.75 1.75 0 0 1 19.25 21H4.75A1.75 1.75 0 0 1 3 19.25v-9.5A1.75 1.75 0 0 1 4.75 8M7.5 8L12 3.5L16.5 8");
}

:global(.ezc_z5bls) {
  d: path("m6.5 18l4-4.5l4 4.5m1-6h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
