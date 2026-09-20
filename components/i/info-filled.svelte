<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="suvk3db8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:info-filled" {...props}></Icon>
<style>
:global(.suvk3db8z) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 18a8 8 0 1 1 0-16a8 8 0 0 1 0 16Zm0-9.071a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1ZM10 7.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2Z");
}

</style>
