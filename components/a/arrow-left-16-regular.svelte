<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ayfybjb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-left-16-regular" {...props}></Icon>
<style>
:global(.ayfybjb1h) {
  fill: currentColor;
  d: path("M13.5 8.5a.5.5 0 0 0 0-1H3.803l4.031-3.628a.5.5 0 1 0-.668-.744l-5 4.5a.5.5 0 0 0 0 .744l5 4.5a.5.5 0 1 0 .668-.744L3.803 8.5z");
}

</style>
