<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pjuqoelhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:currency-eth-thin" {...props}></Icon>
<style>
:global(.pjuqoelhu) {
  fill: currentColor;
  d: path("m219.15 125.53l-88-112a4 4 0 0 0-6.3 0l-88 112a4 4 0 0 0 0 4.94l88 112a4 4 0 0 0 6.3 0l88-112a4 4 0 0 0 0-4.94M132 27.57l77.71 98.9L132 161.79Zm-8 134.22l-77.71-35.32L124 27.57Zm0 8.79v57.85l-70.72-90Zm8 0l70.72-32.15l-70.72 90Z");
}

</style>
