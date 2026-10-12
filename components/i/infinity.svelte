<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzt1k6s4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:infinity" {...props}></Icon>
<style>
:global(.dzt1k6s4g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-1.75-2.25-3.5-3.75-5.25-3.75a3.75 3.75 0 0 0 0 7.5c1.75 0 3.5-1.5 5.25-3.75m0 0c1.75 2.25 3.5 3.75 5.25 3.75a3.75 3.75 0 0 0 0-7.5c-1.75 0-3.5 1.5-5.25 3.75");
}

</style>
