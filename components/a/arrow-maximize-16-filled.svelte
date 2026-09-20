<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z168vib-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-maximize-16-filled" {...props}></Icon>
<style>
:global(.z168vib-h) {
  fill: currentColor;
  d: path("M12.75 2.5a.75.75 0 0 1 .75.75v5a.75.75 0 0 1-1.5 0V5.06L5.06 12h3.19a.75.75 0 0 1 0 1.5h-5a.75.75 0 0 1-.75-.75v-5a.75.75 0 0 1 1.5 0v3.19L10.94 4H7.75a.75.75 0 0 1 0-1.5z");
}

</style>
