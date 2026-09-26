<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8ee98bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plug" {...props}></Icon>
<style>
:global(.i8ee98bou) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7L16 7C17.6569 7 19 8.3431 19 10L19 11C19 14.866 15.866 18 12 18C8.134 18 5 14.866 5 11L5 10C5 8.3431 6.3431 7 8 7ZM9 2L9 7M15 2L15 7M12 18L12 22");
}

</style>
