<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyvv5qbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:barn-sharp" {...props}></Icon>
<style>
:global(.pyvv5qbay) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l5 3l3 4v11H4V10l3-4zM3 21h18M9 21v-5h6v5m-5-11a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
