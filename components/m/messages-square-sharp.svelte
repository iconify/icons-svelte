<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sov4fmbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:messages-square-sharp" {...props}></Icon>
<style>
:global(.sov4fmbdd) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10L21 10L21 21L18 18L12 18L12 10ZM6.2929 12.7071L3 16L3 3L17 3");
}

</style>
