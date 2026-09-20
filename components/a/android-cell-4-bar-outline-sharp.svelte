<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ti_9jxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:android-cell-4-bar-outline-sharp" {...props}></Icon>
<style>
:global(.k6ti_9jxu) {
  fill: currentColor;
  d: path("M2.866 19v-6.577h1.692V19zm5.519 0v-8.884h1.692V19zm5.519 0V7.789h1.692V19zm5.519 0V5h1.693v14z");
}

</style>
