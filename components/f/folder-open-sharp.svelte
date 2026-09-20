<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af8j7_b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:folder-open-sharp" {...props}></Icon>
<style>
:global(.af8j7_b1l) {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2h9.231v1H4v9.962l2.266-7.577h16.6L20.288 19z");
}

</style>
