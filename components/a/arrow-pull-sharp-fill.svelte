<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-srupb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-pull-sharp-fill" {...props}></Icon>
<style>
:global(.i-srupb8n) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2V23M13.293 5.2929L10 2L6.707 5.2929M10 10C10 13.3 12.82 15.8056 17 17L17.725 17.2072");
}

</style>
