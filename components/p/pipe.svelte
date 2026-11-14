<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9r3dkb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pipe" {...props}></Icon>
<style>
:global(.r9r3dkb2w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v7m0 5v7");
}

</style>
