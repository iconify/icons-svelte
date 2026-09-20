<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jrwm7dkhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-right-32-regular" {...props}></Icon>
<style>
:global(.jrwm7dkhc) {
  fill: currentColor;
  d: path("M3 16a1 1 0 0 1 1-1h21.586l-8.293-8.293a1 1 0 0 1 1.414-1.414l10 10a1 1 0 0 1 0 1.414l-10 10a1 1 0 0 1-1.414-1.414L25.586 17H4a1 1 0 0 1-1-1");
}

</style>
