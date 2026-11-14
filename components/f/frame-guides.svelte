<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt5e8_ufc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frame-guides" {...props}></Icon>
<style>
:global(.xt5e8_ufc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 5m2.75 0v14m6.5-14v14M2.5 9.75h19m-19 4.5h19");
}

</style>
