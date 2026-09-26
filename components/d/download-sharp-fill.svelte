<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnm9yk__a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:download-sharp-fill" {...props}></Icon>
<style>
:global(.nnm9yk__a) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L12 14M7.7071 9.7071L12 14L16.2929 9.7071M4 17L4 21L20 21L20 17");
}

</style>
