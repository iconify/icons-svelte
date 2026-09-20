<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gax97-omy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:exclamation-mark-light" {...props}></Icon>
<style>
:global(.gax97-omy) {
  fill: currentColor;
  d: path("M142 200a14 14 0 1 1-14-14a14 14 0 0 1 14 14m-14-42a6 6 0 0 0 6-6V48a6 6 0 0 0-12 0v104a6 6 0 0 0 6 6");
}

</style>
