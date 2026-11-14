<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbj5hmbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bridge-symbol" {...props}></Icon>
<style>
:global(.lbj5hmbrw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h19v12H18a6 6 0 0 0-12 0H2.5Zm0 3h19");
}

</style>
