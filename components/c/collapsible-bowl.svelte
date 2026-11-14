<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4_bp825n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:collapsible-bowl" {...props}></Icon>
<style>
:global(.m4_bp825n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18l-3 10.5H6Zm1 3.5h16M5 14h14");
}

</style>
