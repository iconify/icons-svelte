<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phptf4mdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x2-check-sharp" {...props}></Icon>
<style>
:global(.phptf4mdm) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 11L20 11L20 2L2 2L2 20L11 20L11 2M15.7055 19.2971L18.3333 22L22.1467 15.76");
}

</style>
