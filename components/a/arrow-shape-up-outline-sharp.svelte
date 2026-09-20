<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icu55rbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-shape-up-outline-sharp" {...props}></Icon>
<style>
:global(.icu55rbyl) {
  fill: currentColor;
  d: path("M8.539 20v-5.808H4L12 5l8 9.192h-4.538V20zm1-1h4.923v-5.808h3.352L12 6.535l-5.813 6.657h3.352zM12 13.192");
}

</style>
