<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a193-jb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:align-right-text" {...props}></Icon>
<style>
:global(.a193-jb-k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5h17M9.5 10h11m-17 4.5h17M12 19h8.5");
}

</style>
