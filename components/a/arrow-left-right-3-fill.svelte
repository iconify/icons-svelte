<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0m5hqbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-left-right-3-fill" {...props}></Icon>
<style>
:global(.j0m5hqbuj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 17L21.2604 17M17.1053 12L21.8633 16.6759C22.0456 16.8549 22.0456 17.1451 21.8633 17.3241L17.1053 22M13 7L2.7396 7M6.8947 12L2.1367 7.3241C1.9544 7.1451 1.9544 6.8549 2.1367 6.6759L6.8947 2");
}

</style>
