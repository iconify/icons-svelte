<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3gn7pbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:notebook-sharp" {...props}></Icon>
<style>
:global(.y3gn7pbwd) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 2L21 2L21 22L5 22L5 2ZM2 7L8 7M2 12L8 12M2 17L8 17M17 5L17 19");
}

</style>
