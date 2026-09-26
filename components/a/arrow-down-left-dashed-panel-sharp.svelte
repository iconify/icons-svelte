<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edpp-ebii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-left-dashed-panel-sharp" {...props}></Icon>
<style>
:global(.edpp-ebii) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10.5L3 21L13.5 21M3.1464 20.8536L12.7929 11.2071M9.5 3L14.5 3M21 9.5L21 14.5M3 8L3 3L7 3M17 3L21 3L21 7M16 21L21.0001 21L21 17");
}

</style>
