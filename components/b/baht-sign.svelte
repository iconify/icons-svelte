<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cro4ckb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baht-sign" {...props}></Icon>
<style>
:global(.cro4ckb-w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12H13a3.75 3.75 0 0 0 0-7.5H7.5v15H14a3.75 3.75 0 0 0 0-7.5m-3-9.5v19");
}

</style>
