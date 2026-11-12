<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqvsjvbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:boolean-union-fill-round" {...props}></Icon>
<style>
:global(.kqvsjvbxw) {
  fill: currentColor;
  d: path("M13 2a3 3 0 0 1 3 3v2a.997.997 0 0 0 1 1h2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3v-2a.997.997 0 0 0-1-1H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Z");
}

</style>
