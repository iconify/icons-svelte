<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjw4ic7sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flexibility-score" {...props}></Icon>
<style>
:global(.pjw4ic7sg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5v5m19-5v5M2.5 12h11.75m5 0h2.25m-7.25 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
