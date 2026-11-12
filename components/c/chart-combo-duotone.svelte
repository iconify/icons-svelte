<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr88hyb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-combo-duotone" {...props}></Icon>
<style>
:global(.yr88hyb3g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16v4m6-6v6m6-8v8M3 4v14a2 2 0 0 0 2 2h16M3 11l6-6l6 4l6-6");
}

</style>
