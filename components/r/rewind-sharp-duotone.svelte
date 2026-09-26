<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq2_qrlix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rewind-sharp-duotone" {...props}></Icon>
<style>
:global(.cq2_qrlix) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 17.998L13.5417 12L22 6.002L22 17.998ZM10 17.998L2 12L10 6.002L10 17.998Z");
}

</style>
