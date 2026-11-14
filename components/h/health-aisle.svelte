<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iln6a9b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:health-aisle" {...props}></Icon>
<style>
:global(.iln6a9b0y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5v19m16-19v19M4 11h16M4 19h16M7 11V8a2 2 0 0 1 2-2V4h2v2a2 2 0 0 1 2 2v3m-.5 3h3a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
