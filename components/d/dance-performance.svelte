<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czcnm0t8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dance-performance" {...props}></Icon>
<style>
:global(.czcnm0t8o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M3.5 6.5l10 3.25L21 9.5m-7.5.25L11 14.5M3 18l8-3.5l7 7");
}

</style>
