<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhljnxb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pool-skimmer" {...props}></Icon>
<style>
:global(.fhljnxb4d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h4a3.5 3.5 0 0 1 3.5 3.5v1A3.5 3.5 0 0 1 10 11H6a3.5 3.5 0 0 1-3.5-3.5v-1A3.5 3.5 0 0 1 6 3m6 8l8.5 9.5M2.5 7h11M8 3v8");
}

</style>
