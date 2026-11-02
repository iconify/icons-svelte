<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jamjth_ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:network-sharp" {...props}></Icon>
<style>
:global(.jamjth_ei) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h6v5H9ZM3 16h6v5H3Zm12 0h6v5h-6Zm-3-8v4m-6 4v-4h12v4");
}

</style>
