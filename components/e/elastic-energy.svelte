<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-le_qbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:elastic-energy" {...props}></Icon>
<style>
:global(.o-le_qbat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h16m-16 17h16m-8-17l5.5 3l-11 3.5l11 3.75l-11 3.75l5.5 3");
}

</style>
