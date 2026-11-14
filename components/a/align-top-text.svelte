<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbf38z0ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:align-top-text" {...props}></Icon>
<style>
:global(.cbf38z0ej) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17M6 8h12M6 12h8");
}

</style>
