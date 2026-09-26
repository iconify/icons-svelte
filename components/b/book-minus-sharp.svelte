<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi94aubdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-minus-sharp" {...props}></Icon>
<style>
:global(.zi94aubdz) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 13L20 2L4 2L4 22M11 22L4 22L4 18L11 18M8 6L8 14M13 19L21 19");
}

</style>
