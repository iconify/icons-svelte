<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9jys6klb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ad-fraud" {...props}></Icon>
<style>
:global(.x9jys6klb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3L3 20h18zm0 5v5m0 3h.01");
}

</style>
