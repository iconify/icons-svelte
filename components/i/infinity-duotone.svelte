<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejzu5je1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:infinity-duotone" {...props}></Icon>
<style>
:global(.ejzu5je1m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16c4 0 6-8 10-8a4 4 0 1 1 0 8c-4 0-6-8-10-8m0 0a4 4 0 1 0 0 8");
}

</style>
