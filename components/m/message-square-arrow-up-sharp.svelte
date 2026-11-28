<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfsxb0bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-arrow-up-sharp" {...props}></Icon>
<style>
:global(.dfsxb0bkr) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 17L7 17L3 21L3 3ZM12 14L12 7M8.7071 10.2929L12 7L15.2929 10.2929");
}

</style>
