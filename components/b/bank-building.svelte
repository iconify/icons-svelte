<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2sdwpb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bank-building" {...props}></Icon>
<style>
:global(.j2sdwpb8l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9a5.5 5.5 0 0 1 11 0m-14 0h17M3 20h18M12 2v1.5m-5.5 8.25v5.5m3.75-5.5v5.5m3.5-5.5v5.5m3.75-5.5v5.5");
}

</style>
