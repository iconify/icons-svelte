<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag1r62bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flower-border" {...props}></Icon>
<style>
:global(.ag1r62bfp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5h19M3 9l2 1.5L7 9v2.5a2 2 0 0 1-4 0Zm7-4.5L12 6l2-1.5V7a2 2 0 0 1-4 0ZM17 9l2 1.5L21 9v2.5a2 2 0 0 1-4 0ZM5 13.5v6M12 9v10.5m7-6v6");
}

</style>
