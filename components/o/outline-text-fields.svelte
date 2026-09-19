<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gibl43_-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-text-fields" {...props}></Icon>
<style>
:global(.gibl43_-b) {
  fill: currentColor;
  d: path("M2.5 4v3h5v12h3V7h5V4zm19 5h-9v3h3v7h3v-7h3z");
}

</style>
