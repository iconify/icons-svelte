<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-kvw07u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ratio" {...props}></Icon>
<style>
:global(.qa-kvw07u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 6.5l2-2v15m11-13l2-2v15M12 9h.01M12 15h.01");
}

</style>
