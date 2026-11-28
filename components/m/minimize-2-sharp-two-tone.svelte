<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auzxo4s4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:minimize-2-sharp-two-tone" {...props}></Icon>
<style>
:global(.auzxo4s4d) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 2L9 9L2 9M2.7071 2.7071L8.8243 8.8243M15 2L15 9L22 9M21.2929 2.7071L15.1757 8.8243M15 22L15 15L22 15M21.2929 21.2929L15.1757 15.1757M9 22L9 15L2 15M2.7071 21.2929L8.8243 15.1757");
}

</style>
