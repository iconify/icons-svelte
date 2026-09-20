<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4m8ghb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dialpad-48-regular" {...props}></Icon>
<style>
:global(.w4m8ghb2c) {
  fill: currentColor;
  d: path("M16 8.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m0 10a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m0 10a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m10.5-20a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m0 10a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m0 10a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m0 10a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0M37 8.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m0 10a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m0 10a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0");
}

</style>
