<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cushkugar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:batch-norm" {...props}></Icon>
<style>
:global(.cushkugar) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20c4.5 0 5.5-13.5 9-13.5S16.5 20 21 20M2.5 20h19M12 4v16");
}

</style>
