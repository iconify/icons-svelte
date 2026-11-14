<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9tc5wpcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fishing-chair" {...props}></Icon>
<style>
:global(.k9tc5wpcr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11h12M5 11L4 3.5M5 11l12 9.5m0-9.5L5 20.5m-1-17h8.5");
}

</style>
