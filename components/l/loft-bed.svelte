<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3q9jtxzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:loft-bed" {...props}></Icon>
<style>
:global(.k3q9jtxzi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5V3m18 18.5V3M3 10.5h18m-18-4h11m2 4v11m0-7.5h5m-5 3.75h5");
}

</style>
