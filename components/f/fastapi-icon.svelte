<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v_89xsb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:fastapi-icon" {...props}></Icon>
<style>
:global(.v_89xsb5o) {
  fill: var(--svg-color--009688, #009688);
  d: path("M128 0C57.33 0 0 57.33 0 128s57.33 128 128 128s128-57.33 128-128S198.67 0 128 0m-6.67 230.605v-80.288H76.699l64.128-124.922v80.288h42.966z");
}

</style>
