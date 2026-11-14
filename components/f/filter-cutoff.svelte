<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_oqgdcru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:filter-cutoff" {...props}></Icon>
<style>
:global(.t_oqgdcru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9H12c3.5 0 5 2.5 9.5 10M12 2.5V5m0 2.75v2.5M12 13v2.5m0 2.75v2.5");
}

</style>
