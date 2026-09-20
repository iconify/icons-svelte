<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k8thgdbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-right-20-filled" {...props}></Icon>
<style>
:global(.k8thgdbil) {
  fill: currentColor;
  d: path("M8 3.75A.75.75 0 0 1 8.75 3h7.5a.75.75 0 0 1 .75.75v7.5a.75.75 0 1 1-1.5 0V5.56L4.28 16.78a.75.75 0 0 1-1.06-1.06L14.44 4.5H8.75A.75.75 0 0 1 8 3.75");
}

</style>
