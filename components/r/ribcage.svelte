<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km_emsbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ribcage" {...props}></Icon>
<style>
:global(.km_emsbud) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v18M12 5c-3 0-7 .5-7 3.5m7 1.25c-3 0-7 .5-7 3.5m7 1.25c-3 0-7 .5-7 3.5m7-13c3 0 7 .5 7 3.5m-7 1.25c3 0 7 .5 7 3.5m-7 1.25c3 0 7 .5 7 3.5");
}

</style>
