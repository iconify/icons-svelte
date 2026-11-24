<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av031sbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:download-duotone" {...props}></Icon>
<style>
:global(.av031sbfh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 12l4 4l4-4m-4 4V4M4 16v2a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-2");
}

</style>
