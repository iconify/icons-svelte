<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9spwacck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-dashed-sharp" {...props}></Icon>
<style>
:global(.y9spwacck) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9L3 3L21 3L21 9L3 9ZM3 17L3 21L7 21M17 21L21 21L21 17M3 12L3 15M21 12L21 15M9.5 21L14.5 21");
}

</style>
