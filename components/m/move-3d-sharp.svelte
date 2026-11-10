<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi9ygjq4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:move-3d-sharp" {...props}></Icon>
<style>
:global(.pi9ygjq4y) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.619 16.28L11.998 13M11.998 13L16.377 16.28M11.998 13V9.49M7.96 9.49L11.998 3L16.036 9.49H7.96ZM19.132 13.53L20.996 21L13.527 19.13L19.132 13.53ZM4.865 13.53L3 21L10.469 19.13L4.865 13.53Z");
}

</style>
