<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghb4gnb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:risk-probability" {...props}></Icon>
<style>
:global(.ghb4gnb5r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20C6 20 7.5 4 12 4s6 16 9.5 16M12 4v16.5");
}

</style>
