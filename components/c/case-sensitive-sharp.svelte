<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz8fuvhmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:case-sensitive-sharp" {...props}></Icon>
<style>
:global(.iz8fuvhmn) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.9417 19.1631L7 5L12.0583 19.1631M3.7857 14L10.2143 14M22 16C22 17.6569 20.6569 19 19 19C17.3431 19 16 17.6569 16 16C16 14.3431 17.3431 13 19 13C20.6569 13 22 14.3431 22 16ZM22 11L22 20");
}

</style>
