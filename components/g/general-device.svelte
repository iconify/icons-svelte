<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vegny2bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:general-device" {...props}></Icon>
<style>
:global(.vegny2bbg) {
  fill: currentColor;
  d: path("M8.77 17V5.616q0-.667.474-1.141Q9.72 4 10.386 4h3.234q.667 0 1.139.475q.472.474.472 1.14V17zm0 2.385v-1h6.46v1z");
}

</style>
