<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8nqld6vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-2-arrow-up-sharp" {...props}></Icon>
<style>
:global(.s8nqld6vj) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 3L22 3L22 17L2 17ZM12 17L12 21M7 21L17 21M12 14L12 7M8.7071 10.2929L12 7L15.2929 10.2929");
}

</style>
