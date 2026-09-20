<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sudjambsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:park" {...props}></Icon>
<style>
:global(.sudjambsc) {
  fill: currentColor;
  d: path("M12.989 21H11.01v-4H4.885l4-6H6.922L12 3.73L17.077 11h-1.961l4 6h-6.127z");
}

</style>
