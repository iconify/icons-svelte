<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tguzdo5-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barre-class" {...props}></Icon>
<style>
:global(.tguzdo5-e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19M6 5.5v13m-2.5 0h5m9.5-13v13m-2.5 0h5");
}

</style>
