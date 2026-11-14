<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knmqa4bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-fashion" {...props}></Icon>
<style>
:global(.knmqa4bma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 6l-8 5l2.5 3l2-1.5v8h7v-8l2 1.5l2.5-3zM9.5 4c0-1.25 2.5-1.25 2.5.5");
}

</style>
