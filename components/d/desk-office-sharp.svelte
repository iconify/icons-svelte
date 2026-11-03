<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4a5dnbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:desk-office-sharp" {...props}></Icon>
<style>
:global(.n4a5dnbfz) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 23L3 12L21 12L21 22L14 22L14 11M21 17L14 17M12 12L12 8M7 8L7 2L17 2L17 8L7 8Z");
}

</style>
