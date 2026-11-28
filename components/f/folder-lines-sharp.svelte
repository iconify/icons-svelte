<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl5e4hbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-lines-sharp" {...props}></Icon>
<style>
:global(.kl5e4hbzu) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4L9.5 4L12 6.5L21 6.5L21 20L3 20L3 4ZM7 11L17 11M7 15L14 15");
}

</style>
