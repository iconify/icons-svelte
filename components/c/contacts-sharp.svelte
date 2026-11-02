<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_z5xddyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:contacts-sharp" {...props}></Icon>
<style>
:global(.t_z5xddyd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3h14v18H5Zm14 5h2m-2 8h2M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0M8 21a4 4 0 1 1 8 0");
}

</style>
