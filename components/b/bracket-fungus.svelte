<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wouzrwi_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bracket-fungus" {...props}></Icon>
<style>
:global(.wouzrwi_e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19m3.5-19v19m0-16h14a7 5.5 0 0 1-14 0m0 8.5h12a6 4.5 0 0 1-12 0");
}

</style>
