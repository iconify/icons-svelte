<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqx_kmb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flag-triangle" {...props}></Icon>
<style>
:global(.qqx_kmb3b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.831 4.82l6.477 2.279a1.75 1.75 0 0 1 0 3.302L8.831 12.68A1.75 1.75 0 0 1 6.5 11.029V6.471A1.75 1.75 0 0 1 8.831 4.82M6.5 3v18");
}

</style>
