<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh-qo7bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:magnification-large-sharp" {...props}></Icon>
<style>
:global(.yh-qo7bkq) {
  fill: currentColor;
  d: path("M5.5 14.5h11v-7h-11zM3 19V5h18v14z");
}

</style>
