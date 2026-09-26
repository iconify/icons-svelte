<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz1dp7iva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines-sharp-fill" {...props}></Icon>
<style>
:global(.lz1dp7iva) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9L4 15M8 5L8 19M12 2L12 22M16 6L16 18M20 9L20 15");
}

</style>
