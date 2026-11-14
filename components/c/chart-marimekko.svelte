<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shm_26hpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-marimekko" {...props}></Icon>
<style>
:global(.shm_26hpq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 2.5h13.75A2.625 2.625 0 0 1 21.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875V5.125A2.625 2.625 0 0 1 5.125 2.5m5.375 0v19m5-19v19m-13-12h8m0 5h5m0-7.5h6");
}

</style>
