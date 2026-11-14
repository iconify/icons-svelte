<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze6_fbbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ab-wheel" {...props}></Icon>
<style>
:global(.ze6_fbbgq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5zA2.5 2.5 0 0 1 14.5 7v10a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 17V7A2.5 2.5 0 0 1 12 4.5M2.5 12h7m5 0h7");
}

</style>
