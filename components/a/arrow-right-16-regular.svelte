<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pnztc1lzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-right-16-regular" {...props}></Icon>
<style>
:global(.pnztc1lzq) {
  fill: currentColor;
  d: path("M2.5 7.5a.5.5 0 1 0 0 1h9.697l-4.031 3.628a.5.5 0 1 0 .668.744l5-4.5a.5.5 0 0 0 0-.744l-5-4.5a.5.5 0 0 0-.668.744L12.197 7.5z");
}

</style>
