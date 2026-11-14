<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-ajwgb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:road-snow" {...props}></Icon>
<style>
:global(.u-ajwgb0a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5L6 15m14.5 6.5L18 15m-6 1.5v4M12 3v9m3.897-6.75l-7.794 4.5m7.794 0l-7.794-4.5");
}

</style>
