<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tojw6vlav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clapperboard-sharp" {...props}></Icon>
<style>
:global(.tojw6vlav) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 21L3 21ZM3 8L21 8M6.5 8L8.5 3M11 8L13 3M15.5 8L17.5 3");
}

</style>
