<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clymk1bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-checklist-duotone-round" {...props}></Icon>
<style>
:global(.clymk1bpk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 6h8m-8 6h8m-8 6h8M3 6l2 2l4-4m-6 8l2 2l4-4m-6 8l2 2l4-4");
}

</style>
