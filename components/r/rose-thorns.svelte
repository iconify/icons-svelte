<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="japhhzdmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rose-thorns" {...props}></Icon>
<style>
:global(.japhhzdmd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M12 5L6.75 3.75L12 8.25m0 2L17.25 9L12 13.5m0 2l-5.25-1.25l5.25 4.5");
}

</style>
