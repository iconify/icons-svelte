<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntllq-e3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pentagon-sharp-duotone" {...props}></Icon>
<style>
:global(.ntllq-e3u) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.0022 10.5712L6.2741 21.0003L17.7259 21.0003L20.9978 10.5712L12 2.9997Z");
}

</style>
