<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plnmp502a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:good-service" {...props}></Icon>
<style>
:global(.plnmp502a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 10l5 5l10-10M5 18.5h14m-17 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m17 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
