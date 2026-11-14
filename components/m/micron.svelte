<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_r2ofjzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:micron" {...props}></Icon>
<style>
:global(.u_r2ofjzf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13v5h18v-5M7.5 15.5V18m4.5-3v3m4.5-2.5V18M9.75 7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
