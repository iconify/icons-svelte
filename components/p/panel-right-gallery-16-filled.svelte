<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kionpfrgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-right-gallery-16-filled" {...props}></Icon>
<style>
:global(.kionpfrgl) {
  fill: currentColor;
  d: path("M14 5.5A2.5 2.5 0 0 0 11.5 3h-7A2.5 2.5 0 0 0 2 5.5v5A2.5 2.5 0 0 0 4.5 13h7a2.5 2.5 0 0 0 2.5-2.5V10h-4v2H4.5A1.5 1.5 0 0 1 3 10.5v-5A1.5 1.5 0 0 1 4.5 4H10v2h4zM14 7h-4v2h4z");
}

</style>
