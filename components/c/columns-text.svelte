<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6bcq9bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:columns-text" {...props}></Icon>
<style>
:global(.c6bcq9bpg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h7m-7 4.75h7m-7 4.75h7m-7 4.75h7m2.5-14.25h7m-7 4.75h7m-7 4.75h7m-7 4.75h4.5");
}

</style>
