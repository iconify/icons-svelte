<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnexsebdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:key-round" {...props}></Icon>
<style>
:global(.pnexsebdn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 8a5 5 0 1 0 10 0a5 5 0 1 0-10 0m1.5 3.5l-9 9m3-3l2 2M17 7h.01");
}

</style>
