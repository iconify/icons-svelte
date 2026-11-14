<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbo5j5b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:joystick" {...props}></Icon>
<style>
:global(.wbo5j5b_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 15h16v6H4Zm8 0V9.5m-3.5-3a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM16 18h.01");
}

</style>
