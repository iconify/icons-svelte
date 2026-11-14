<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufyp3zpbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bowled-out" {...props}></Icon>
<style>
:global(.ufyp3zpbp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10v11.5M12 10v11.5M16 10v11.5m-9.5-15l3.5-2m3.5-.5L17 6");
}

</style>
