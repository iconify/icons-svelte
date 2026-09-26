<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2o6wxl9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-check-sharp" {...props}></Icon>
<style>
:global(.l2o6wxl9b) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 13L20 2L4 2L4 22M11 22L4 22L4 18L11 18M8 6L8 14M13.7071 18.7071L16 21L20.2929 16.7071");
}

</style>
