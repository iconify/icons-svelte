<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5yjy8bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-right-sharp" {...props}></Icon>
<style>
:global(.t5yjy8bij) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.7071 17.2929L11 12L5.7071 6.7071M12.7071 17.2929L18 12L12.7071 6.7071");
}

</style>
