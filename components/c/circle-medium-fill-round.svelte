<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr3_-mb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-medium-fill-round" {...props}></Icon>
<style>
:global(.yr3_-mb_s) {
  fill: currentColor;
  d: path("M5.551 9.275a7 7 0 0 1 9.173-3.723a7 7 0 0 1 3.724 9.172A7 7 0 0 1 5.551 9.275");
}

</style>
