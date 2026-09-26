<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra01bjbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mouse-sharp" {...props}></Icon>
<style>
:global(.ra01bjbbm) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3C15.3137 3 18 5.6863 18 9L18 15C18 18.3137 15.3137 21 12 21C8.6863 21 6 18.3137 6 15L6 9C6 5.6863 8.6863 3 12 3ZM12 6L12 9");
}

</style>
