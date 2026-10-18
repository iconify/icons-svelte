<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxyvm1b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-left-dash-sharp" {...props}></Icon>
<style>
:global(.fxyvm1b2m) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12L10 20L10 16L18 16L18 8L10 8L10 4ZM22 7L22 17");
}

</style>
