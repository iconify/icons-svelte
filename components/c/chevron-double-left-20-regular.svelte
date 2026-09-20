<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tfmas8sdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-double-left-20-regular" {...props}></Icon>
<style>
:global(.tfmas8sdw) {
  fill: currentColor;
  d: path("M9.646 4.146a.5.5 0 1 1 .707.708L5.208 10l5.147 5.147a.5.5 0 1 1-.708.707l-5.5-5.5a.5.5 0 0 1 0-.708zm5 0a.5.5 0 1 1 .707.708L10.208 10l5.147 5.147a.5.5 0 1 1-.707.707l-5.5-5.5a.5.5 0 0 1 0-.708z");
}

</style>
