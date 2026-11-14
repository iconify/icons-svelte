<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ds7ye6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:firework-roman-candle" {...props}></Icon>
<style>
:global(.y0ds7ye6m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12.5h6v9H9Zm3 0q0-2 1.5-2.5M9 8L5.5 3M12 7V2.5M15.5 8L19 3");
}

</style>
