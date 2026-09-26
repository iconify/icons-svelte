<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e757wub0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plug-sharp" {...props}></Icon>
<style>
:global(.e757wub0o) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7L19 7L19 11C19 14.866 15.866 18 12 18C8.134 18 5 14.866 5 11L5 7ZM9 1L9 7M15 1L15 7M12 18L12 23");
}

</style>
