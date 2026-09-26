<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsujqd_kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-sharp" {...props}></Icon>
<style>
:global(.hsujqd_kx) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 20L2 20L2 4ZM2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7");
}

</style>
