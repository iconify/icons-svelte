<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ppkrx937v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-vertical-32-regular" {...props}></Icon>
<style>
:global(.ppkrx937v) {
  fill: currentColor;
  d: path("M16 9.5a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5m0 9a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5M13.5 25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0");
}

</style>
