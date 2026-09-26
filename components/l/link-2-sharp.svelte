<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctjez13cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:link-2-sharp" {...props}></Icon>
<style>
:global(.ctjez13cp) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 17L7 17C4.2386 17 2 14.7614 2 12C2 9.2386 4.2386 7 7 7L10 7M14 7L17 7C19.7614 7 22 9.2386 22 12C22 14.7614 19.7614 17 17 17L14 17M7 12L17 12");
}

</style>
