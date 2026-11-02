<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr5p_h15c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-8-duocolor-sharp" {...props}></Icon>
<style>
:global(.nr5p_h15c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11a4 4 0 1 1 0-8m0 8a4 4 0 1 0 0-8m0 8a5 5 0 0 0 0 10m0-10a5 5 0 0 1 0 10");
}

</style>
