<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cln1ozisj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gravity-physics" {...props}></Icon>
<style>
:global(.cln1ozisj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M3 20.5h18M18 5v10m-2.5-2.5L18 15l2.5-2.5");
}

</style>
