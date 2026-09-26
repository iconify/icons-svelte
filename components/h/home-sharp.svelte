<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlgxmq6ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:home-sharp" {...props}></Icon>
<style>
:global(.hlgxmq6ep) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 10L12 2.9963L3 10L3 21L21 21L21 10ZM9 21L9 14L15 14L15 21");
}

</style>
