<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc_odpbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gazebo" {...props}></Icon>
<style>
:global(.hc_odpbpv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5v-1L12 3l9.5 5.5v1Zm2.5 0V21M19 9.5V21M12 9.5V21m-7-5h14");
}

</style>
