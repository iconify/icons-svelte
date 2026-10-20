<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4kt7zbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:copy-minus-sharp" {...props}></Icon>
<style>
:global(.s4kt7zbie) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 5L16.0001 2L2 2L2 16.0001L5 16M8 8L22 8L22 22L8 22L8 8ZM11 15L19 15");
}

</style>
