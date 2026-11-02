<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptvi5kbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:navigation-round" {...props}></Icon>
<style>
:global(.ptvi5kbkd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l6 2c1.107.369.476 2.262-1 3l-2 1a6.7 6.7 0 0 0-3 3l-1 2c-.738 1.476-2.631 2.107-3 1L4 6c-.412-1.236.764-2.412 2-2z");
}

</style>
