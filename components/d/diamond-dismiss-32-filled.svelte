<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tyr84kb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:diamond-dismiss-32-filled" {...props}></Icon>
<style>
:global(.tyr84kb0w) {
  fill: currentColor;
  d: path("M12.817 2.318a4.5 4.5 0 0 1 6.364 0L29.68 12.817a4.5 4.5 0 0 1 0 6.364L19.181 29.68a4.5 4.5 0 0 1-6.364 0l-10.5-10.499a4.5 4.5 0 0 1 0-6.364zm8.39 8.475a1 1 0 0 0-1.414 0L16 14.586l-3.793-3.793a1 1 0 0 0-1.414 1.414L14.586 16l-3.793 3.793a1 1 0 0 0 1.414 1.414L16 17.414l3.793 3.793a1 1 0 0 0 1.414-1.414L17.414 16l3.793-3.793a1 1 0 0 0 0-1.414");
}

</style>
