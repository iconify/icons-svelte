<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtgcc1b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:account-tree-sharp" {...props}></Icon>
<style>
:global(.rtgcc1b_b) {
  fill: currentColor;
  d: path("M15.5 20.5v-3h-4v-10h-3v3h-6v-7h6v3h7v-3h6v7h-6v-3h-3v9h3v-3h6v7z");
}

</style>
