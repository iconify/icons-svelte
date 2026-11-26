<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7aftbbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layers-arrow-down-sharp" {...props}></Icon>
<style>
:global(.p7aftbbhv) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4.001L11.998 6.75L7 9.499L2.002 6.75ZM1.4472 12.0326L7 14.809L12.5528 12.0326M1.4472 17.2826L7 20.059L12.5528 17.2826M15 21L23 21M19 2L19 17M15.7071 13.7071L19 17L22.2929 13.7071");
}

</style>
