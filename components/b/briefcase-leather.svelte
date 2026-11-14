<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn1rrebqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:briefcase-leather" {...props}></Icon>
<style>
:global(.pn1rrebqc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.5h11A3.5 3.5 0 0 1 21 11v6a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17v-6a3.5 3.5 0 0 1 3.5-3.5m2.5 0v-2A1.5 1.5 0 0 1 10.5 4h3A1.5 1.5 0 0 1 15 5.5v2M3 12h18M8 7.5v7.25m8-7.25v7.25");
}

</style>
