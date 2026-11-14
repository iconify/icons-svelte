<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_m57byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:domino-chain" {...props}></Icon>
<style>
:global(.xd_m57byy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.355 5.91l2.853.927L5.5 18.25l-2.853-.927ZM12 6.25h3v12h-3Zm6 0h3v12h-3ZM4.501 11.617l2.853.927M12 12.25h3m3 0h3");
}

</style>
