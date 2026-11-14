<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo-sfcbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:curling-broom" {...props}></Icon>
<style>
:global(.zo-sfcbvp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v10m-2.17 0h4.34a1.75 1.75 0 0 1 1.686 1.282l1.528 5.5a1.75 1.75 0 0 1-1.686 2.218H8.302a1.75 1.75 0 0 1-1.686-2.218l1.528-5.5A1.75 1.75 0 0 1 9.83 12.5m-.33 4h5");
}

</style>
