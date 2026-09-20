<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-bzoyiqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:calendar-view-month-outline-sharp" {...props}></Icon>
<style>
:global(.f-bzoyiqr) {
  fill: currentColor;
  d: path("M4 11h4V6H4zm6 0h4V6h-4zm6 0h4V6h-4zM4 18h4v-5H4zm6 0h4v-5h-4zm6 0h4v-5h-4zM2 20V4h20v16z");
}

</style>
