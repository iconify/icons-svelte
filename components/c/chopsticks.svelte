<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx0sbxb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chopsticks" {...props}></Icon>
<style>
:global(.bx0sbxb5o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 20.5l10-17m-6 17l10-17");
}

</style>
